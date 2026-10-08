---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights
title: Customer Experience Insights roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Customer Experience Insights. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Customer Experience Insights roles

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
<td>Contact Center AI Insights Admin
<p>( <code>roles/ contactcenterinsights.admin</code> )</p>
<p>Grants full access to all Contact Center AI Insights resources.</p></td>
<td><p><code>contactcenterinsights.*</code></p>
<ul>
<li><code>contactcenterinsights. analyses. create</code></li>
<li><code>contactcenterinsights. analyses. delete</code></li>
<li><code>contactcenterinsights. analyses. get</code></li>
<li><code>contactcenterinsights. analyses. list</code></li>
<li><code>contactcenterinsights. analysisRules. create</code></li>
<li><code>contactcenterinsights. analysisRules. delete</code></li>
<li><code>contactcenterinsights. analysisRules. get</code></li>
<li><code>contactcenterinsights. analysisRules. list</code></li>
<li><code>contactcenterinsights. analysisRules. update</code></li>
<li><code>contactcenterinsights. assessmentRules. create</code></li>
<li><code>contactcenterinsights. assessmentRules. delete</code></li>
<li><code>contactcenterinsights. assessmentRules. get</code></li>
<li><code>contactcenterinsights. assessmentRules. list</code></li>
<li><code>contactcenterinsights. assessmentRules. update</code></li>
<li><code>contactcenterinsights. assessments. appeal</code></li>
<li><code>contactcenterinsights. assessments. create</code></li>
<li><code>contactcenterinsights. assessments. delete</code></li>
<li><code>contactcenterinsights. assessments. finalize</code></li>
<li><code>contactcenterinsights. assessments. get</code></li>
<li><code>contactcenterinsights. assessments. list</code></li>
<li><code>contactcenterinsights. assessments. publish</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. create</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. delete</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. get</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. list</code></li>
<li><code>contactcenterinsights. authorizedAssessments. appeal</code></li>
<li><code>contactcenterinsights. authorizedAssessments. create</code></li>
<li><code>contactcenterinsights. authorizedAssessments. delete</code></li>
<li><code>contactcenterinsights. authorizedAssessments. finalize</code></li>
<li><code>contactcenterinsights. authorizedAssessments. get</code></li>
<li><code>contactcenterinsights. authorizedAssessments. list</code></li>
<li><code>contactcenterinsights. authorizedAssessments. publish</code></li>
<li><code>contactcenterinsights. authorizedConversations. create</code></li>
<li><code>contactcenterinsights. authorizedConversations. delete</code></li>
<li><code>contactcenterinsights. authorizedConversations. generateSignedAudio</code></li>
<li><code>contactcenterinsights. authorizedConversations. get</code></li>
<li><code>contactcenterinsights. authorizedConversations. list</code></li>
<li><code>contactcenterinsights. authorizedConversations. update</code></li>
<li><code>contactcenterinsights. authorizedConversations. upload</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. create</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. delete</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. download</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. get</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. list</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. update</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. upload</code></li>
<li><code>contactcenterinsights. authorizedNotes. create</code></li>
<li><code>contactcenterinsights. authorizedNotes. delete</code></li>
<li><code>contactcenterinsights. authorizedNotes. list</code></li>
<li><code>contactcenterinsights. authorizedNotes. update</code></li>
<li><code>contactcenterinsights. authorizedOperations. get</code></li>
<li><code>contactcenterinsights. authorizedOperations. list</code></li>
<li><code>contactcenterinsights. authorizedViewSets. create</code></li>
<li><code>contactcenterinsights. authorizedViewSets. delete</code></li>
<li><code>contactcenterinsights. authorizedViewSets. get</code></li>
<li><code>contactcenterinsights. authorizedViewSets. list</code></li>
<li><code>contactcenterinsights. authorizedViewSets. update</code></li>
<li><code>contactcenterinsights. authorizedViews. create</code></li>
<li><code>contactcenterinsights. authorizedViews. delete</code></li>
<li><code>contactcenterinsights. authorizedViews. get</code></li>
<li><code>contactcenterinsights. authorizedViews. getIamPolicy</code></li>
<li><code>contactcenterinsights. authorizedViews. list</code></li>
<li><code>contactcenterinsights. authorizedViews. setIamPolicy</code></li>
<li><code>contactcenterinsights. authorizedViews. update</code></li>
<li><code>contactcenterinsights. conversations. create</code></li>
<li><code>contactcenterinsights. conversations. delete</code></li>
<li><code>contactcenterinsights. conversations. export</code></li>
<li><code>contactcenterinsights. conversations. generateSignedAudio</code></li>
<li><code>contactcenterinsights. conversations. get</code></li>
<li><code>contactcenterinsights. conversations. list</code></li>
<li><code>contactcenterinsights. conversations. update</code></li>
<li><code>contactcenterinsights. conversations. upload</code></li>
<li><code>contactcenterinsights. datasetAnalyses. create</code></li>
<li><code>contactcenterinsights. datasetAnalyses. delete</code></li>
<li><code>contactcenterinsights. datasetAnalyses. get</code></li>
<li><code>contactcenterinsights. datasetAnalyses. list</code></li>
<li><code>contactcenterinsights. datasetConversations. create</code></li>
<li><code>contactcenterinsights. datasetConversations. delete</code></li>
<li><code>contactcenterinsights. datasetConversations. export</code></li>
<li><code>contactcenterinsights. datasetConversations. generateSignedAudio</code></li>
<li><code>contactcenterinsights. datasetConversations. get</code></li>
<li><code>contactcenterinsights. datasetConversations. list</code></li>
<li><code>contactcenterinsights. datasetConversations. update</code></li>
<li><code>contactcenterinsights. datasetConversations. upload</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. create</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. delete</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. download</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. get</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. list</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. update</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. upload</code></li>
<li><code>contactcenterinsights. datasets. create</code></li>
<li><code>contactcenterinsights. datasets. delete</code></li>
<li><code>contactcenterinsights. datasets. get</code></li>
<li><code>contactcenterinsights. datasets. list</code></li>
<li><code>contactcenterinsights. datasets. update</code></li>
<li><code>contactcenterinsights. diagnostics. create</code></li>
<li><code>contactcenterinsights. diagnostics. delete</code></li>
<li><code>contactcenterinsights. diagnostics. get</code></li>
<li><code>contactcenterinsights. diagnostics. list</code></li>
<li><code>contactcenterinsights. discoveries. delete</code></li>
<li><code>contactcenterinsights. discoveries. generate</code></li>
<li><code>contactcenterinsights. discoveries. get</code></li>
<li><code>contactcenterinsights. discoveries. list</code></li>
<li><code>contactcenterinsights. discoveries. update</code></li>
<li><code>contactcenterinsights. discoveryResults. get</code></li>
<li><code>contactcenterinsights. discoveryResults. list</code></li>
<li><code>contactcenterinsights. discoveryRevisions. create</code></li>
<li><code>contactcenterinsights. discoveryRevisions. get</code></li>
<li><code>contactcenterinsights. discoveryRevisions. list</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. delete</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. deploy</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. fetchTree</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. get</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. list</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. undeploy</code></li>
<li><code>contactcenterinsights. encryptionSpecs. get</code></li>
<li><code>contactcenterinsights. encryptionSpecs. initialize</code></li>
<li><code>contactcenterinsights. faqEntries. delete</code></li>
<li><code>contactcenterinsights. faqEntries. get</code></li>
<li><code>contactcenterinsights. faqEntries. list</code></li>
<li><code>contactcenterinsights. faqEntries. update</code></li>
<li><code>contactcenterinsights. faqModels. create</code></li>
<li><code>contactcenterinsights. faqModels. delete</code></li>
<li><code>contactcenterinsights. faqModels. get</code></li>
<li><code>contactcenterinsights. faqModels. list</code></li>
<li><code>contactcenterinsights. faqModels. update</code></li>
<li><code>contactcenterinsights. feedbackLabels. create</code></li>
<li><code>contactcenterinsights. feedbackLabels. delete</code></li>
<li><code>contactcenterinsights. feedbackLabels. download</code></li>
<li><code>contactcenterinsights. feedbackLabels. get</code></li>
<li><code>contactcenterinsights. feedbackLabels. list</code></li>
<li><code>contactcenterinsights. feedbackLabels. update</code></li>
<li><code>contactcenterinsights. feedbackLabels. upload</code></li>
<li><code>contactcenterinsights. issueModels. create</code></li>
<li><code>contactcenterinsights. issueModels. delete</code></li>
<li><code>contactcenterinsights. issueModels. deploy</code></li>
<li><code>contactcenterinsights. issueModels. export</code></li>
<li><code>contactcenterinsights. issueModels. get</code></li>
<li><code>contactcenterinsights. issueModels. import</code></li>
<li><code>contactcenterinsights. issueModels. list</code></li>
<li><code>contactcenterinsights. issueModels. undeploy</code></li>
<li><code>contactcenterinsights. issueModels. update</code></li>
<li><code>contactcenterinsights. issues. create</code></li>
<li><code>contactcenterinsights. issues. delete</code></li>
<li><code>contactcenterinsights. issues. get</code></li>
<li><code>contactcenterinsights. issues. list</code></li>
<li><code>contactcenterinsights. issues. update</code></li>
<li><code>contactcenterinsights. notes. create</code></li>
<li><code>contactcenterinsights. notes. delete</code></li>
<li><code>contactcenterinsights. notes. list</code></li>
<li><code>contactcenterinsights. notes. update</code></li>
<li><code>contactcenterinsights. operations. cancel</code></li>
<li><code>contactcenterinsights. operations. get</code></li>
<li><code>contactcenterinsights. operations. list</code></li>
<li><code>contactcenterinsights. phraseMatchers. create</code></li>
<li><code>contactcenterinsights. phraseMatchers. delete</code></li>
<li><code>contactcenterinsights. phraseMatchers. get</code></li>
<li><code>contactcenterinsights. phraseMatchers. list</code></li>
<li><code>contactcenterinsights. phraseMatchers. update</code></li>
<li><code>contactcenterinsights. qaQuestionTags. create</code></li>
<li><code>contactcenterinsights. qaQuestionTags. delete</code></li>
<li><code>contactcenterinsights. qaQuestionTags. get</code></li>
<li><code>contactcenterinsights. qaQuestionTags. list</code></li>
<li><code>contactcenterinsights. qaQuestionTags. update</code></li>
<li><code>contactcenterinsights. qaQuestions. create</code></li>
<li><code>contactcenterinsights. qaQuestions. delete</code></li>
<li><code>contactcenterinsights. qaQuestions. get</code></li>
<li><code>contactcenterinsights. qaQuestions. list</code></li>
<li><code>contactcenterinsights. qaQuestions. update</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. bulkUpdateQaQuestions</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. create</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. delete</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. deploy</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. get</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. list</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. tune</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. undeploy</code></li>
<li><code>contactcenterinsights. qaScorecards. create</code></li>
<li><code>contactcenterinsights. qaScorecards. delete</code></li>
<li><code>contactcenterinsights. qaScorecards. get</code></li>
<li><code>contactcenterinsights. qaScorecards. list</code></li>
<li><code>contactcenterinsights. qaScorecards. update</code></li>
<li><code>contactcenterinsights. settings. get</code></li>
<li><code>contactcenterinsights. settings. update</code></li>
<li><code>contactcenterinsights. views. create</code></li>
<li><code>contactcenterinsights. views. delete</code></li>
<li><code>contactcenterinsights. views. get</code></li>
<li><code>contactcenterinsights. views. list</code></li>
<li><code>contactcenterinsights. views. update</code></li>
<li><code>contactcenterinsights. visibilityLabels. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Contact Center AI Insights editor
<p>( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Grants read and write access to all Contact Center AI Insights resources.</p></td>
<td><p><code>contactcenterinsights. analyses.*</code></p>
<ul>
<li><code>contactcenterinsights. analyses. create</code></li>
<li><code>contactcenterinsights. analyses. delete</code></li>
<li><code>contactcenterinsights. analyses. get</code></li>
<li><code>contactcenterinsights. analyses. list</code></li>
</ul>
<p><code>contactcenterinsights. analysisRules.*</code></p>
<ul>
<li><code>contactcenterinsights. analysisRules. create</code></li>
<li><code>contactcenterinsights. analysisRules. delete</code></li>
<li><code>contactcenterinsights. analysisRules. get</code></li>
<li><code>contactcenterinsights. analysisRules. list</code></li>
<li><code>contactcenterinsights. analysisRules. update</code></li>
</ul>
<p><code>contactcenterinsights. assessmentRules.*</code></p>
<ul>
<li><code>contactcenterinsights. assessmentRules. create</code></li>
<li><code>contactcenterinsights. assessmentRules. delete</code></li>
<li><code>contactcenterinsights. assessmentRules. get</code></li>
<li><code>contactcenterinsights. assessmentRules. list</code></li>
<li><code>contactcenterinsights. assessmentRules. update</code></li>
</ul>
<p><code>contactcenterinsights. assessments.*</code></p>
<ul>
<li><code>contactcenterinsights. assessments. appeal</code></li>
<li><code>contactcenterinsights. assessments. create</code></li>
<li><code>contactcenterinsights. assessments. delete</code></li>
<li><code>contactcenterinsights. assessments. finalize</code></li>
<li><code>contactcenterinsights. assessments. get</code></li>
<li><code>contactcenterinsights. assessments. list</code></li>
<li><code>contactcenterinsights. assessments. publish</code></li>
</ul>
<p><code>contactcenterinsights. authorizedAnalyses.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedAnalyses. create</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. delete</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. get</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. list</code></li>
</ul>
<p><code>contactcenterinsights. authorizedAssessments.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedAssessments. appeal</code></li>
<li><code>contactcenterinsights. authorizedAssessments. create</code></li>
<li><code>contactcenterinsights. authorizedAssessments. delete</code></li>
<li><code>contactcenterinsights. authorizedAssessments. finalize</code></li>
<li><code>contactcenterinsights. authorizedAssessments. get</code></li>
<li><code>contactcenterinsights. authorizedAssessments. list</code></li>
<li><code>contactcenterinsights. authorizedAssessments. publish</code></li>
</ul>
<p><code>contactcenterinsights. authorizedConversations.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedConversations. create</code></li>
<li><code>contactcenterinsights. authorizedConversations. delete</code></li>
<li><code>contactcenterinsights. authorizedConversations. generateSignedAudio</code></li>
<li><code>contactcenterinsights. authorizedConversations. get</code></li>
<li><code>contactcenterinsights. authorizedConversations. list</code></li>
<li><code>contactcenterinsights. authorizedConversations. update</code></li>
<li><code>contactcenterinsights. authorizedConversations. upload</code></li>
</ul>
<p><code>contactcenterinsights. authorizedFeedbackLabels.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedFeedbackLabels. create</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. delete</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. download</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. get</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. list</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. update</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. upload</code></li>
</ul>
<p><code>contactcenterinsights. authorizedNotes.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedNotes. create</code></li>
<li><code>contactcenterinsights. authorizedNotes. delete</code></li>
<li><code>contactcenterinsights. authorizedNotes. list</code></li>
<li><code>contactcenterinsights. authorizedNotes. update</code></li>
</ul>
<p><code>contactcenterinsights. authorizedOperations.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedOperations. get</code></li>
<li><code>contactcenterinsights. authorizedOperations. list</code></li>
</ul>
<p><code>contactcenterinsights. authorizedViewSets.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedViewSets. create</code></li>
<li><code>contactcenterinsights. authorizedViewSets. delete</code></li>
<li><code>contactcenterinsights. authorizedViewSets. get</code></li>
<li><code>contactcenterinsights. authorizedViewSets. list</code></li>
<li><code>contactcenterinsights. authorizedViewSets. update</code></li>
</ul>
<p><code>contactcenterinsights. authorizedViews. create</code></p>
<p><code>contactcenterinsights. authorizedViews. delete</code></p>
<p><code>contactcenterinsights. authorizedViews. get</code></p>
<p><code>contactcenterinsights. authorizedViews. list</code></p>
<p><code>contactcenterinsights. authorizedViews. update</code></p>
<p><code>contactcenterinsights. conversations.*</code></p>
<ul>
<li><code>contactcenterinsights. conversations. create</code></li>
<li><code>contactcenterinsights. conversations. delete</code></li>
<li><code>contactcenterinsights. conversations. export</code></li>
<li><code>contactcenterinsights. conversations. generateSignedAudio</code></li>
<li><code>contactcenterinsights. conversations. get</code></li>
<li><code>contactcenterinsights. conversations. list</code></li>
<li><code>contactcenterinsights. conversations. update</code></li>
<li><code>contactcenterinsights. conversations. upload</code></li>
</ul>
<p><code>contactcenterinsights. datasetAnalyses.*</code></p>
<ul>
<li><code>contactcenterinsights. datasetAnalyses. create</code></li>
<li><code>contactcenterinsights. datasetAnalyses. delete</code></li>
<li><code>contactcenterinsights. datasetAnalyses. get</code></li>
<li><code>contactcenterinsights. datasetAnalyses. list</code></li>
</ul>
<p><code>contactcenterinsights. datasetConversations.*</code></p>
<ul>
<li><code>contactcenterinsights. datasetConversations. create</code></li>
<li><code>contactcenterinsights. datasetConversations. delete</code></li>
<li><code>contactcenterinsights. datasetConversations. export</code></li>
<li><code>contactcenterinsights. datasetConversations. generateSignedAudio</code></li>
<li><code>contactcenterinsights. datasetConversations. get</code></li>
<li><code>contactcenterinsights. datasetConversations. list</code></li>
<li><code>contactcenterinsights. datasetConversations. update</code></li>
<li><code>contactcenterinsights. datasetConversations. upload</code></li>
</ul>
<p><code>contactcenterinsights. datasetFeedbackLabels.*</code></p>
<ul>
<li><code>contactcenterinsights. datasetFeedbackLabels. create</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. delete</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. download</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. get</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. list</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. update</code></li>
<li><code>contactcenterinsights. datasetFeedbackLabels. upload</code></li>
</ul>
<p><code>contactcenterinsights. datasets.*</code></p>
<ul>
<li><code>contactcenterinsights. datasets. create</code></li>
<li><code>contactcenterinsights. datasets. delete</code></li>
<li><code>contactcenterinsights. datasets. get</code></li>
<li><code>contactcenterinsights. datasets. list</code></li>
<li><code>contactcenterinsights. datasets. update</code></li>
</ul>
<p><code>contactcenterinsights. diagnostics.*</code></p>
<ul>
<li><code>contactcenterinsights. diagnostics. create</code></li>
<li><code>contactcenterinsights. diagnostics. delete</code></li>
<li><code>contactcenterinsights. diagnostics. get</code></li>
<li><code>contactcenterinsights. diagnostics. list</code></li>
</ul>
<p><code>contactcenterinsights. discoveries.*</code></p>
<ul>
<li><code>contactcenterinsights. discoveries. delete</code></li>
<li><code>contactcenterinsights. discoveries. generate</code></li>
<li><code>contactcenterinsights. discoveries. get</code></li>
<li><code>contactcenterinsights. discoveries. list</code></li>
<li><code>contactcenterinsights. discoveries. update</code></li>
</ul>
<p><code>contactcenterinsights. discoveryResults.*</code></p>
<ul>
<li><code>contactcenterinsights. discoveryResults. get</code></li>
<li><code>contactcenterinsights. discoveryResults. list</code></li>
</ul>
<p><code>contactcenterinsights. discoveryRevisions.*</code></p>
<ul>
<li><code>contactcenterinsights. discoveryRevisions. create</code></li>
<li><code>contactcenterinsights. discoveryRevisions. get</code></li>
<li><code>contactcenterinsights. discoveryRevisions. list</code></li>
</ul>
<p><code>contactcenterinsights. discoveryWorkspaces.*</code></p>
<ul>
<li><code>contactcenterinsights. discoveryWorkspaces. delete</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. deploy</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. fetchTree</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. get</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. list</code></li>
<li><code>contactcenterinsights. discoveryWorkspaces. undeploy</code></li>
</ul>
<p><code>contactcenterinsights. encryptionSpecs.*</code></p>
<ul>
<li><code>contactcenterinsights. encryptionSpecs. get</code></li>
<li><code>contactcenterinsights. encryptionSpecs. initialize</code></li>
</ul>
<p><code>contactcenterinsights. faqEntries.*</code></p>
<ul>
<li><code>contactcenterinsights. faqEntries. delete</code></li>
<li><code>contactcenterinsights. faqEntries. get</code></li>
<li><code>contactcenterinsights. faqEntries. list</code></li>
<li><code>contactcenterinsights. faqEntries. update</code></li>
</ul>
<p><code>contactcenterinsights. faqModels.*</code></p>
<ul>
<li><code>contactcenterinsights. faqModels. create</code></li>
<li><code>contactcenterinsights. faqModels. delete</code></li>
<li><code>contactcenterinsights. faqModels. get</code></li>
<li><code>contactcenterinsights. faqModels. list</code></li>
<li><code>contactcenterinsights. faqModels. update</code></li>
</ul>
<p><code>contactcenterinsights. feedbackLabels.*</code></p>
<ul>
<li><code>contactcenterinsights. feedbackLabels. create</code></li>
<li><code>contactcenterinsights. feedbackLabels. delete</code></li>
<li><code>contactcenterinsights. feedbackLabels. download</code></li>
<li><code>contactcenterinsights. feedbackLabels. get</code></li>
<li><code>contactcenterinsights. feedbackLabels. list</code></li>
<li><code>contactcenterinsights. feedbackLabels. update</code></li>
<li><code>contactcenterinsights. feedbackLabels. upload</code></li>
</ul>
<p><code>contactcenterinsights. issueModels.*</code></p>
<ul>
<li><code>contactcenterinsights. issueModels. create</code></li>
<li><code>contactcenterinsights. issueModels. delete</code></li>
<li><code>contactcenterinsights. issueModels. deploy</code></li>
<li><code>contactcenterinsights. issueModels. export</code></li>
<li><code>contactcenterinsights. issueModels. get</code></li>
<li><code>contactcenterinsights. issueModels. import</code></li>
<li><code>contactcenterinsights. issueModels. list</code></li>
<li><code>contactcenterinsights. issueModels. undeploy</code></li>
<li><code>contactcenterinsights. issueModels. update</code></li>
</ul>
<p><code>contactcenterinsights.issues.*</code></p>
<ul>
<li><code>contactcenterinsights. issues. create</code></li>
<li><code>contactcenterinsights. issues. delete</code></li>
<li><code>contactcenterinsights. issues. get</code></li>
<li><code>contactcenterinsights. issues. list</code></li>
<li><code>contactcenterinsights. issues. update</code></li>
</ul>
<p><code>contactcenterinsights.notes.*</code></p>
<ul>
<li><code>contactcenterinsights. notes. create</code></li>
<li><code>contactcenterinsights. notes. delete</code></li>
<li><code>contactcenterinsights. notes. list</code></li>
<li><code>contactcenterinsights. notes. update</code></li>
</ul>
<p><code>contactcenterinsights. operations.*</code></p>
<ul>
<li><code>contactcenterinsights. operations. cancel</code></li>
<li><code>contactcenterinsights. operations. get</code></li>
<li><code>contactcenterinsights. operations. list</code></li>
</ul>
<p><code>contactcenterinsights. phraseMatchers.*</code></p>
<ul>
<li><code>contactcenterinsights. phraseMatchers. create</code></li>
<li><code>contactcenterinsights. phraseMatchers. delete</code></li>
<li><code>contactcenterinsights. phraseMatchers. get</code></li>
<li><code>contactcenterinsights. phraseMatchers. list</code></li>
<li><code>contactcenterinsights. phraseMatchers. update</code></li>
</ul>
<p><code>contactcenterinsights. qaQuestionTags.*</code></p>
<ul>
<li><code>contactcenterinsights. qaQuestionTags. create</code></li>
<li><code>contactcenterinsights. qaQuestionTags. delete</code></li>
<li><code>contactcenterinsights. qaQuestionTags. get</code></li>
<li><code>contactcenterinsights. qaQuestionTags. list</code></li>
<li><code>contactcenterinsights. qaQuestionTags. update</code></li>
</ul>
<p><code>contactcenterinsights. qaQuestions.*</code></p>
<ul>
<li><code>contactcenterinsights. qaQuestions. create</code></li>
<li><code>contactcenterinsights. qaQuestions. delete</code></li>
<li><code>contactcenterinsights. qaQuestions. get</code></li>
<li><code>contactcenterinsights. qaQuestions. list</code></li>
<li><code>contactcenterinsights. qaQuestions. update</code></li>
</ul>
<p><code>contactcenterinsights. qaScorecardRevisions.*</code></p>
<ul>
<li><code>contactcenterinsights. qaScorecardRevisions. bulkUpdateQaQuestions</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. create</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. delete</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. deploy</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. get</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. list</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. tune</code></li>
<li><code>contactcenterinsights. qaScorecardRevisions. undeploy</code></li>
</ul>
<p><code>contactcenterinsights. qaScorecards.*</code></p>
<ul>
<li><code>contactcenterinsights. qaScorecards. create</code></li>
<li><code>contactcenterinsights. qaScorecards. delete</code></li>
<li><code>contactcenterinsights. qaScorecards. get</code></li>
<li><code>contactcenterinsights. qaScorecards. list</code></li>
<li><code>contactcenterinsights. qaScorecards. update</code></li>
</ul>
<p><code>contactcenterinsights. settings.*</code></p>
<ul>
<li><code>contactcenterinsights. settings. get</code></li>
<li><code>contactcenterinsights. settings. update</code></li>
</ul>
<p><code>contactcenterinsights.views.*</code></p>
<ul>
<li><code>contactcenterinsights. views. create</code></li>
<li><code>contactcenterinsights. views. delete</code></li>
<li><code>contactcenterinsights. views. get</code></li>
<li><code>contactcenterinsights. views. list</code></li>
<li><code>contactcenterinsights. views. update</code></li>
</ul>
<p><code>contactcenterinsights. visibilityLabels. list</code></p></td>
</tr>
<tr class="odd">
<td>Contact Center AI Insights viewer
<p>( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p>Grants read access to all Contact Center AI Insights resources.</p></td>
<td><p><code>contactcenterinsights. analyses. get</code></p>
<p><code>contactcenterinsights. analyses. list</code></p>
<p><code>contactcenterinsights. analysisRules. get</code></p>
<p><code>contactcenterinsights. analysisRules. list</code></p>
<p><code>contactcenterinsights. assessmentRules. get</code></p>
<p><code>contactcenterinsights. assessmentRules. list</code></p>
<p><code>contactcenterinsights. assessments. get</code></p>
<p><code>contactcenterinsights. assessments. list</code></p>
<p><code>contactcenterinsights. authorizedAnalyses. get</code></p>
<p><code>contactcenterinsights. authorizedAnalyses. list</code></p>
<p><code>contactcenterinsights. authorizedAssessments. get</code></p>
<p><code>contactcenterinsights. authorizedAssessments. list</code></p>
<p><code>contactcenterinsights. authorizedConversations. generateSignedAudio</code></p>
<p><code>contactcenterinsights. authorizedConversations. get</code></p>
<p><code>contactcenterinsights. authorizedConversations. list</code></p>
<p><code>contactcenterinsights. authorizedFeedbackLabels. get</code></p>
<p><code>contactcenterinsights. authorizedFeedbackLabels. list</code></p>
<p><code>contactcenterinsights. authorizedNotes. list</code></p>
<p><code>contactcenterinsights. authorizedOperations.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedOperations. get</code></li>
<li><code>contactcenterinsights. authorizedOperations. list</code></li>
</ul>
<p><code>contactcenterinsights. authorizedViewSets. get</code></p>
<p><code>contactcenterinsights. authorizedViewSets. list</code></p>
<p><code>contactcenterinsights. authorizedViews. get</code></p>
<p><code>contactcenterinsights. authorizedViews. list</code></p>
<p><code>contactcenterinsights. conversations. generateSignedAudio</code></p>
<p><code>contactcenterinsights. conversations. get</code></p>
<p><code>contactcenterinsights. conversations. list</code></p>
<p><code>contactcenterinsights. datasetAnalyses. get</code></p>
<p><code>contactcenterinsights. datasetAnalyses. list</code></p>
<p><code>contactcenterinsights. datasetConversations. generateSignedAudio</code></p>
<p><code>contactcenterinsights. datasetConversations. get</code></p>
<p><code>contactcenterinsights. datasetConversations. list</code></p>
<p><code>contactcenterinsights. datasetFeedbackLabels. get</code></p>
<p><code>contactcenterinsights. datasetFeedbackLabels. list</code></p>
<p><code>contactcenterinsights. datasets. get</code></p>
<p><code>contactcenterinsights. datasets. list</code></p>
<p><code>contactcenterinsights. diagnostics. get</code></p>
<p><code>contactcenterinsights. diagnostics. list</code></p>
<p><code>contactcenterinsights. discoveries. get</code></p>
<p><code>contactcenterinsights. discoveries. list</code></p>
<p><code>contactcenterinsights. discoveryResults.*</code></p>
<ul>
<li><code>contactcenterinsights. discoveryResults. get</code></li>
<li><code>contactcenterinsights. discoveryResults. list</code></li>
</ul>
<p><code>contactcenterinsights. discoveryRevisions. get</code></p>
<p><code>contactcenterinsights. discoveryRevisions. list</code></p>
<p><code>contactcenterinsights. discoveryWorkspaces. fetchTree</code></p>
<p><code>contactcenterinsights. discoveryWorkspaces. get</code></p>
<p><code>contactcenterinsights. discoveryWorkspaces. list</code></p>
<p><code>contactcenterinsights. encryptionSpecs. get</code></p>
<p><code>contactcenterinsights. faqEntries. get</code></p>
<p><code>contactcenterinsights. faqEntries. list</code></p>
<p><code>contactcenterinsights. faqModels. get</code></p>
<p><code>contactcenterinsights. faqModels. list</code></p>
<p><code>contactcenterinsights. feedbackLabels. download</code></p>
<p><code>contactcenterinsights. feedbackLabels. get</code></p>
<p><code>contactcenterinsights. feedbackLabels. list</code></p>
<p><code>contactcenterinsights. issueModels. get</code></p>
<p><code>contactcenterinsights. issueModels. list</code></p>
<p><code>contactcenterinsights. issues. get</code></p>
<p><code>contactcenterinsights. issues. list</code></p>
<p><code>contactcenterinsights. notes. list</code></p>
<p><code>contactcenterinsights. operations. get</code></p>
<p><code>contactcenterinsights. operations. list</code></p>
<p><code>contactcenterinsights. phraseMatchers. get</code></p>
<p><code>contactcenterinsights. phraseMatchers. list</code></p>
<p><code>contactcenterinsights. qaQuestionTags. get</code></p>
<p><code>contactcenterinsights. qaQuestionTags. list</code></p>
<p><code>contactcenterinsights. qaQuestions. get</code></p>
<p><code>contactcenterinsights. qaQuestions. list</code></p>
<p><code>contactcenterinsights. qaScorecardRevisions. get</code></p>
<p><code>contactcenterinsights. qaScorecardRevisions. list</code></p>
<p><code>contactcenterinsights. qaScorecards. get</code></p>
<p><code>contactcenterinsights. qaScorecards. list</code></p>
<p><code>contactcenterinsights. settings. get</code></p>
<p><code>contactcenterinsights. views. get</code></p>
<p><code>contactcenterinsights. views. list</code></p>
<p><code>contactcenterinsights. visibilityLabels. list</code></p></td>
</tr>
<tr class="even">
<td>Contact Center AI Insights authorized editor <sup>Beta</sup>
<p>( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p>Grants read and write access to Authorized resources.</p></td>
<td><p><code>contactcenterinsights. authorizedAnalyses.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedAnalyses. create</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. delete</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. get</code></li>
<li><code>contactcenterinsights. authorizedAnalyses. list</code></li>
</ul>
<p><code>contactcenterinsights. authorizedAssessments.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedAssessments. appeal</code></li>
<li><code>contactcenterinsights. authorizedAssessments. create</code></li>
<li><code>contactcenterinsights. authorizedAssessments. delete</code></li>
<li><code>contactcenterinsights. authorizedAssessments. finalize</code></li>
<li><code>contactcenterinsights. authorizedAssessments. get</code></li>
<li><code>contactcenterinsights. authorizedAssessments. list</code></li>
<li><code>contactcenterinsights. authorizedAssessments. publish</code></li>
</ul>
<p><code>contactcenterinsights. authorizedConversations.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedConversations. create</code></li>
<li><code>contactcenterinsights. authorizedConversations. delete</code></li>
<li><code>contactcenterinsights. authorizedConversations. generateSignedAudio</code></li>
<li><code>contactcenterinsights. authorizedConversations. get</code></li>
<li><code>contactcenterinsights. authorizedConversations. list</code></li>
<li><code>contactcenterinsights. authorizedConversations. update</code></li>
<li><code>contactcenterinsights. authorizedConversations. upload</code></li>
</ul>
<p><code>contactcenterinsights. authorizedFeedbackLabels.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedFeedbackLabels. create</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. delete</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. download</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. get</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. list</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. update</code></li>
<li><code>contactcenterinsights. authorizedFeedbackLabels. upload</code></li>
</ul>
<p><code>contactcenterinsights. authorizedNotes.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedNotes. create</code></li>
<li><code>contactcenterinsights. authorizedNotes. delete</code></li>
<li><code>contactcenterinsights. authorizedNotes. list</code></li>
<li><code>contactcenterinsights. authorizedNotes. update</code></li>
</ul>
<p><code>contactcenterinsights. authorizedOperations.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedOperations. get</code></li>
<li><code>contactcenterinsights. authorizedOperations. list</code></li>
</ul>
<p><code>contactcenterinsights. authorizedViewSets. get</code></p>
<p><code>contactcenterinsights. authorizedViewSets. list</code></p>
<p><code>contactcenterinsights. authorizedViews. get</code></p>
<p><code>contactcenterinsights. authorizedViews. list</code></p></td>
</tr>
<tr class="odd">
<td>Contact Center AI Insights authorized viewer <sup>Beta</sup>
<p>( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p>Grants read access to Authorized resources.</p></td>
<td><p><code>contactcenterinsights. authorizedAnalyses. get</code></p>
<p><code>contactcenterinsights. authorizedAnalyses. list</code></p>
<p><code>contactcenterinsights. authorizedAssessments. get</code></p>
<p><code>contactcenterinsights. authorizedAssessments. list</code></p>
<p><code>contactcenterinsights. authorizedConversations. generateSignedAudio</code></p>
<p><code>contactcenterinsights. authorizedConversations. get</code></p>
<p><code>contactcenterinsights. authorizedConversations. list</code></p>
<p><code>contactcenterinsights. authorizedFeedbackLabels. get</code></p>
<p><code>contactcenterinsights. authorizedFeedbackLabels. list</code></p>
<p><code>contactcenterinsights. authorizedNotes. list</code></p>
<p><code>contactcenterinsights. authorizedOperations.*</code></p>
<ul>
<li><code>contactcenterinsights. authorizedOperations. get</code></li>
<li><code>contactcenterinsights. authorizedOperations. list</code></li>
</ul>
<p><code>contactcenterinsights. authorizedViewSets. get</code></p>
<p><code>contactcenterinsights. authorizedViewSets. list</code></p>
<p><code>contactcenterinsights. authorizedViews. get</code></p>
<p><code>contactcenterinsights. authorizedViews. list</code></p></td>
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
<td>Contact Center AI Insights Service Agent
<p>( <code>roles/ contactcenterinsights.serviceAgent</code> )</p>
<p>Allows Contact Center AI to read and write APIs including BigQuery, Dialogflow, and Storage.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.jobs.get</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.update</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>ces.agents.get</code></p>
<p><code>ces.agents.list</code></p>
<p><code>ces.appVersions.get</code></p>
<p><code>ces.appVersions.list</code></p>
<p><code>ces.apps.get</code></p>
<p><code>ces.apps.list</code></p>
<p><code>ces.changelogs.*</code></p>
<ul>
<li><code>ces.changelogs.get</code></li>
<li><code>ces.changelogs.list</code></li>
</ul>
<p><code>ces.deployments.get</code></p>
<p><code>ces.deployments.list</code></p>
<p><code>ces.examples.get</code></p>
<p><code>ces.examples.list</code></p>
<p><code>ces.guardrails.get</code></p>
<p><code>ces.guardrails.list</code></p>
<p><code>ces.tools.get</code></p>
<p><code>ces.tools.list</code></p>
<p><code>ces.toolsets.get</code></p>
<p><code>ces.toolsets.list</code></p>
<p><code>datalabeling.dataitems.*</code></p>
<ul>
<li><code>datalabeling.dataitems.get</code></li>
<li><code>datalabeling.dataitems.list</code></li>
</ul>
<p><code>datalabeling.datasets.create</code></p>
<p><code>datalabeling.datasets.delete</code></p>
<p><code>datalabeling.datasets.export</code></p>
<p><code>datalabeling.datasets.get</code></p>
<p><code>datalabeling.datasets.import</code></p>
<p><code>datalabeling.operations.get</code></p>
<p><code>datalabeling.operations.list</code></p>
<p><code>dialogflow. conversationDatasets.*</code></p>
<ul>
<li><code>dialogflow. conversationDatasets. create</code></li>
<li><code>dialogflow. conversationDatasets. delete</code></li>
<li><code>dialogflow. conversationDatasets. get</code></li>
<li><code>dialogflow. conversationDatasets. import</code></li>
<li><code>dialogflow. conversationDatasets. list</code></li>
</ul>
<p><code>dialogflow. conversationModels.*</code></p>
<ul>
<li><code>dialogflow. conversationModels. create</code></li>
<li><code>dialogflow. conversationModels. delete</code></li>
<li><code>dialogflow. conversationModels. deploy</code></li>
<li><code>dialogflow. conversationModels. get</code></li>
<li><code>dialogflow. conversationModels. list</code></li>
<li><code>dialogflow. conversationModels. undeploy</code></li>
</ul>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow.documents.*</code></p>
<ul>
<li><code>dialogflow.documents.create</code></li>
<li><code>dialogflow.documents.delete</code></li>
<li><code>dialogflow.documents.get</code></li>
<li><code>dialogflow.documents.list</code></li>
</ul>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow. participants. suggest</code></p>
<p><code>dialogflow. sessions. detectIntent</code></p>
<p><code>dlp.deidentifyTemplates.get</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.inspectTemplates.get</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.kms.encrypt</code></p>
<p><code>dlp.locations.*</code></p>
<ul>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
</ul>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>speech.customClasses.get</code></p>
<p><code>speech.operations.get</code></p>
<p><code>speech.phraseSets.get</code></p>
<p><code>speech.recognizers.create</code></p>
<p><code>speech.recognizers.get</code></p>
<p><code>speech.recognizers.recognize</code></p>
<p><code>speech.recognizers.update</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Customer Experience Insights permissions

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
<td><code>contactcenterinsights. analyses. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. analyses. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. analyses. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. analyses. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. analysisRules. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. analysisRules. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. analysisRules. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. analysisRules. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. analysisRules. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. assessmentRules. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. assessmentRules. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. assessmentRules. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. assessmentRules. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. assessmentRules. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. assessments. appeal</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. assessments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. assessments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. assessments. finalize</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. assessments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. assessments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. assessments. publish</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedAnalyses. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedAnalyses. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedAnalyses. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedAnalyses. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedAssessments. appeal</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedAssessments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedAssessments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedAssessments. finalize</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedAssessments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedAssessments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedAssessments. publish</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedConversations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedConversations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedConversations. generateSignedAudio</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedConversations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedConversations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedConversations. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedConversations. upload</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedFeedbackLabels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedFeedbackLabels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedFeedbackLabels. download</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedFeedbackLabels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedFeedbackLabels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedFeedbackLabels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedFeedbackLabels. upload</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedNotes. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedNotes. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedNotes. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedNotes. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedOperations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedOperations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedViewSets. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedViewSets. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedViewSets. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedViewSets. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedViewSets. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedViews. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedViews. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedViews. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedViews. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedViews. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedEditor">Contact Center AI Insights authorized editor</a> ( <code>roles/ contactcenterinsights.authorizedEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.authorizedViewer">Contact Center AI Insights authorized viewer</a> ( <code>roles/ contactcenterinsights.authorizedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. authorizedViews. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. authorizedViews. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. conversations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. conversations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. conversations. export</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. conversations. generateSignedAudio</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. conversations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. conversations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. conversations. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. conversations. upload</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetAnalyses. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetAnalyses. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetAnalyses. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetAnalyses. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetConversations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetConversations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetConversations. export</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetConversations. generateSignedAudio</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetConversations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetConversations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetConversations. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetConversations. upload</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetFeedbackLabels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetFeedbackLabels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetFeedbackLabels. download</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetFeedbackLabels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetFeedbackLabels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasetFeedbackLabels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasetFeedbackLabels. upload</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasets. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasets. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasets. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. datasets. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. datasets. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. diagnostics. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. diagnostics. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. diagnostics. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. diagnostics. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. discoveries. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. discoveries. generate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. discoveries. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. discoveries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. discoveries. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. discoveryResults. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. discoveryResults. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. discoveryRevisions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. discoveryRevisions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. discoveryRevisions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. discoveryWorkspaces. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. discoveryWorkspaces. deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. discoveryWorkspaces. fetchTree</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. discoveryWorkspaces. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. discoveryWorkspaces. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. discoveryWorkspaces. undeploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. encryptionSpecs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. encryptionSpecs. initialize</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. faqEntries. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. faqEntries. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. faqEntries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. faqEntries. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. faqModels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. faqModels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. faqModels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. faqModels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. faqModels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. feedbackLabels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. feedbackLabels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. feedbackLabels. download</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. feedbackLabels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. feedbackLabels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. feedbackLabels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. feedbackLabels. upload</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. issueModels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. issueModels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. issueModels. deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. issueModels. export</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. issueModels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. issueModels. import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. issueModels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. issueModels. undeploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. issueModels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. issues. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. issues. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. issues. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. issues. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. issues. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. notes. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. notes. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. notes. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. notes. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. phraseMatchers. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. phraseMatchers. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. phraseMatchers. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. phraseMatchers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. phraseMatchers. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaQuestionTags. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaQuestionTags. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaQuestionTags. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaQuestionTags. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaQuestionTags. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaQuestions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaQuestions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaQuestions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaQuestions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaQuestions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaScorecardRevisions. bulkUpdateQaQuestions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaScorecardRevisions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaScorecardRevisions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaScorecardRevisions. deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaScorecardRevisions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaScorecardRevisions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaScorecardRevisions. tune</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaScorecardRevisions. undeploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaScorecards. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaScorecards. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaScorecards. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. qaScorecards. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. qaScorecards. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. settings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. settings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. views. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. views. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. views. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. views. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>contactcenterinsights. views. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>contactcenterinsights. visibilityLabels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.admin">Contact Center AI Insights Admin</a> ( <code>roles/ contactcenterinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.editor">Contact Center AI Insights editor</a> ( <code>roles/ contactcenterinsights.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.viewer">Contact Center AI Insights viewer</a> ( <code>roles/ contactcenterinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
