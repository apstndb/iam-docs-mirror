---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dialogflow
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow
title: Dialogflow roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Dialogflow. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Dialogflow roles

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
<td>Dialogflow API Admin
<p>( <code>roles/ dialogflow.admin</code> )</p>
<p>Grant to Dialogflow API admins that need full access to Dialogflow-specific resources. Also see <a href="https://docs.cloud.google.com/dialogflow/docs/access-control">Dialogflow access control</a> .</p>
<blockquote>
<strong>Caution:</strong> Users with permissions to create or modify Dialogflow agent components, such as tools and webhooks, can configure these components to authenticate as the Dialogflow Service Agent using ID tokens. This capability can be used to interact with other Google Cloud services that accept ID token authentication using the permissions granted to the <a href="https://docs.cloud.google.com/iam/docs/service-agents#dialogflow-service-agent">Dialogflow Service Agent</a> . Carefully control who is granted permissions to configure these Dialogflow agent components.
</blockquote>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>dialogflow.*</code></p>
<ul>
<li><code>dialogflow.agents.create</code></li>
<li><code>dialogflow.agents.delete</code></li>
<li><code>dialogflow.agents.export</code></li>
<li><code>dialogflow.agents.get</code></li>
<li><code>dialogflow.agents.import</code></li>
<li><code>dialogflow.agents.list</code></li>
<li><code>dialogflow.agents.restore</code></li>
<li><code>dialogflow.agents.search</code></li>
<li><code>dialogflow. agents. searchResources</code></li>
<li><code>dialogflow.agents.train</code></li>
<li><code>dialogflow.agents.update</code></li>
<li><code>dialogflow.agents.validate</code></li>
<li><code>dialogflow. answerrecords. delete</code></li>
<li><code>dialogflow.answerrecords.get</code></li>
<li><code>dialogflow.answerrecords.list</code></li>
<li><code>dialogflow. answerrecords. update</code></li>
<li><code>dialogflow.callMatchers.create</code></li>
<li><code>dialogflow.callMatchers.delete</code></li>
<li><code>dialogflow.callMatchers.list</code></li>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
<li><code>dialogflow. companionAgents. create</code></li>
<li><code>dialogflow. companionAgents. delete</code></li>
<li><code>dialogflow.companionAgents.get</code></li>
<li><code>dialogflow. companionAgents. list</code></li>
<li><code>dialogflow. companionAgents. update</code></li>
<li><code>dialogflow.contexts.create</code></li>
<li><code>dialogflow.contexts.delete</code></li>
<li><code>dialogflow.contexts.get</code></li>
<li><code>dialogflow.contexts.list</code></li>
<li><code>dialogflow.contexts.update</code></li>
<li><code>dialogflow. conversationDatasets. create</code></li>
<li><code>dialogflow. conversationDatasets. delete</code></li>
<li><code>dialogflow. conversationDatasets. get</code></li>
<li><code>dialogflow. conversationDatasets. import</code></li>
<li><code>dialogflow. conversationDatasets. list</code></li>
<li><code>dialogflow. conversationModels. create</code></li>
<li><code>dialogflow. conversationModels. delete</code></li>
<li><code>dialogflow. conversationModels. deploy</code></li>
<li><code>dialogflow. conversationModels. get</code></li>
<li><code>dialogflow. conversationModels. list</code></li>
<li><code>dialogflow. conversationModels. undeploy</code></li>
<li><code>dialogflow. conversationProfiles. create</code></li>
<li><code>dialogflow. conversationProfiles. delete</code></li>
<li><code>dialogflow. conversationProfiles. get</code></li>
<li><code>dialogflow. conversationProfiles. list</code></li>
<li><code>dialogflow. conversationProfiles. update</code></li>
<li><code>dialogflow. conversations. addPhoneNumber</code></li>
<li><code>dialogflow. conversations. complete</code></li>
<li><code>dialogflow. conversations. create</code></li>
<li><code>dialogflow.conversations.get</code></li>
<li><code>dialogflow.conversations.list</code></li>
<li><code>dialogflow. conversations. update</code></li>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
<li><code>dialogflow.documents.create</code></li>
<li><code>dialogflow.documents.delete</code></li>
<li><code>dialogflow.documents.get</code></li>
<li><code>dialogflow.documents.list</code></li>
<li><code>dialogflow.encryptionspec.get</code></li>
<li><code>dialogflow. encryptionspec. update</code></li>
<li><code>dialogflow.entityTypes.create</code></li>
<li><code>dialogflow. entityTypes. createEntity</code></li>
<li><code>dialogflow.entityTypes.delete</code></li>
<li><code>dialogflow. entityTypes. deleteEntity</code></li>
<li><code>dialogflow.entityTypes.get</code></li>
<li><code>dialogflow.entityTypes.list</code></li>
<li><code>dialogflow.entityTypes.update</code></li>
<li><code>dialogflow. entityTypes. updateEntity</code></li>
<li><code>dialogflow.environments.create</code></li>
<li><code>dialogflow.environments.delete</code></li>
<li><code>dialogflow.environments.get</code></li>
<li><code>dialogflow. environments. getHistory</code></li>
<li><code>dialogflow.environments.list</code></li>
<li><code>dialogflow. environments. lookupHistory</code></li>
<li><code>dialogflow. environments. runContinuousTest</code></li>
<li><code>dialogflow.environments.update</code></li>
<li><code>dialogflow.examples.create</code></li>
<li><code>dialogflow.examples.delete</code></li>
<li><code>dialogflow.examples.get</code></li>
<li><code>dialogflow.examples.list</code></li>
<li><code>dialogflow.examples.update</code></li>
<li><code>dialogflow.experiments.create</code></li>
<li><code>dialogflow.experiments.delete</code></li>
<li><code>dialogflow.experiments.get</code></li>
<li><code>dialogflow.experiments.list</code></li>
<li><code>dialogflow.experiments.update</code></li>
<li><code>dialogflow.flows.create</code></li>
<li><code>dialogflow.flows.delete</code></li>
<li><code>dialogflow.flows.get</code></li>
<li><code>dialogflow.flows.list</code></li>
<li><code>dialogflow.flows.train</code></li>
<li><code>dialogflow.flows.update</code></li>
<li><code>dialogflow.flows.validate</code></li>
<li><code>dialogflow.fulfillments.get</code></li>
<li><code>dialogflow.fulfillments.update</code></li>
<li><code>dialogflow.generators.create</code></li>
<li><code>dialogflow.generators.delete</code></li>
<li><code>dialogflow.generators.get</code></li>
<li><code>dialogflow.generators.list</code></li>
<li><code>dialogflow.generators.update</code></li>
<li><code>dialogflow.integrations.create</code></li>
<li><code>dialogflow.integrations.delete</code></li>
<li><code>dialogflow.integrations.get</code></li>
<li><code>dialogflow.integrations.list</code></li>
<li><code>dialogflow.integrations.update</code></li>
<li><code>dialogflow.intents.create</code></li>
<li><code>dialogflow.intents.delete</code></li>
<li><code>dialogflow.intents.get</code></li>
<li><code>dialogflow.intents.list</code></li>
<li><code>dialogflow.intents.update</code></li>
<li><code>dialogflow. interactionMonitoringAlerts. ack</code></li>
<li><code>dialogflow. interactionMonitoringAlerts. get</code></li>
<li><code>dialogflow. knowledgeBases. create</code></li>
<li><code>dialogflow. knowledgeBases. delete</code></li>
<li><code>dialogflow.knowledgeBases.get</code></li>
<li><code>dialogflow.knowledgeBases.list</code></li>
<li><code>dialogflow. knowledgeBases. update</code></li>
<li><code>dialogflow.messages.list</code></li>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
<li><code>dialogflow.operations.get</code></li>
<li><code>dialogflow.pages.create</code></li>
<li><code>dialogflow.pages.delete</code></li>
<li><code>dialogflow.pages.get</code></li>
<li><code>dialogflow.pages.list</code></li>
<li><code>dialogflow.pages.update</code></li>
<li><code>dialogflow. participants. analyzeContent</code></li>
<li><code>dialogflow.participants.create</code></li>
<li><code>dialogflow.participants.get</code></li>
<li><code>dialogflow.participants.list</code></li>
<li><code>dialogflow. participants. suggest</code></li>
<li><code>dialogflow.participants.update</code></li>
<li><code>dialogflow. phoneNumberOrders. cancel</code></li>
<li><code>dialogflow. phoneNumberOrders. create</code></li>
<li><code>dialogflow. phoneNumberOrders. get</code></li>
<li><code>dialogflow. phoneNumberOrders. list</code></li>
<li><code>dialogflow. phoneNumberOrders. update</code></li>
<li><code>dialogflow.phoneNumbers.delete</code></li>
<li><code>dialogflow.phoneNumbers.list</code></li>
<li><code>dialogflow. phoneNumbers. undelete</code></li>
<li><code>dialogflow.phoneNumbers.update</code></li>
<li><code>dialogflow.playbooks.create</code></li>
<li><code>dialogflow.playbooks.delete</code></li>
<li><code>dialogflow.playbooks.get</code></li>
<li><code>dialogflow.playbooks.list</code></li>
<li><code>dialogflow.playbooks.update</code></li>
<li><code>dialogflow. securitySettings. create</code></li>
<li><code>dialogflow. securitySettings. delete</code></li>
<li><code>dialogflow. securitySettings. get</code></li>
<li><code>dialogflow. securitySettings. list</code></li>
<li><code>dialogflow. securitySettings. update</code></li>
<li><code>dialogflow. sessionEntityTypes. create</code></li>
<li><code>dialogflow. sessionEntityTypes. delete</code></li>
<li><code>dialogflow. sessionEntityTypes. get</code></li>
<li><code>dialogflow. sessionEntityTypes. list</code></li>
<li><code>dialogflow. sessionEntityTypes. update</code></li>
<li><code>dialogflow. sessions. detectIntent</code></li>
<li><code>dialogflow. sessions. streamingDetectIntent</code></li>
<li><code>dialogflow. smartMessagingEntries. create</code></li>
<li><code>dialogflow. smartMessagingEntries. delete</code></li>
<li><code>dialogflow. smartMessagingEntries. get</code></li>
<li><code>dialogflow. smartMessagingEntries. list</code></li>
<li><code>dialogflow. testcases. calculateCoverage</code></li>
<li><code>dialogflow.testcases.create</code></li>
<li><code>dialogflow.testcases.delete</code></li>
<li><code>dialogflow.testcases.export</code></li>
<li><code>dialogflow.testcases.get</code></li>
<li><code>dialogflow.testcases.import</code></li>
<li><code>dialogflow.testcases.list</code></li>
<li><code>dialogflow.testcases.run</code></li>
<li><code>dialogflow.testcases.update</code></li>
<li><code>dialogflow.tools.create</code></li>
<li><code>dialogflow.tools.delete</code></li>
<li><code>dialogflow.tools.get</code></li>
<li><code>dialogflow.tools.list</code></li>
<li><code>dialogflow.tools.update</code></li>
<li><code>dialogflow. transitionRouteGroups. create</code></li>
<li><code>dialogflow. transitionRouteGroups. delete</code></li>
<li><code>dialogflow. transitionRouteGroups. get</code></li>
<li><code>dialogflow. transitionRouteGroups. list</code></li>
<li><code>dialogflow. transitionRouteGroups. update</code></li>
<li><code>dialogflow.versions.create</code></li>
<li><code>dialogflow.versions.delete</code></li>
<li><code>dialogflow.versions.get</code></li>
<li><code>dialogflow.versions.list</code></li>
<li><code>dialogflow.versions.load</code></li>
<li><code>dialogflow.versions.update</code></li>
<li><code>dialogflow.webhooks.create</code></li>
<li><code>dialogflow.webhooks.delete</code></li>
<li><code>dialogflow.webhooks.get</code></li>
<li><code>dialogflow.webhooks.list</code></li>
<li><code>dialogflow.webhooks.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Dialogflow Viewer
<p>( <code>roles/ dialogflow.viewer</code> )</p>
<p>Viewer role for dialogflow</p></td>
<td><p><code>dialogflow.agents.export</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.agents.search</code></p>
<p><code>dialogflow. agents. searchResources</code></p>
<p><code>dialogflow.answerrecords.get</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.*</code></p>
<ul>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
</ul>
<p><code>dialogflow.companionAgents.get</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.get</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.get</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.entityTypes.get</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow. environments. getHistory</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow. environments. lookupHistory</code></p>
<p><code>dialogflow.examples.get</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.get</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.fulfillments.get</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.get</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.get</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts. get</code></p>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
</ul>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow.pages.get</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.get</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. participants. suggest</code></p>
<p><code>dialogflow. phoneNumberOrders. get</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.get</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. get</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. get</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow. testcases. calculateCoverage</code></p>
<p><code>dialogflow.testcases.export</code></p>
<p><code>dialogflow.testcases.get</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.get</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. get</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.get</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.get</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>CX Premium Admin
<p>( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p>An admin has access to all resources and can perform all administrative actions in an AAM project.</p></td>
<td><p><code>dialogflow.agents.export</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.agents.search</code></p>
<p><code>dialogflow. agents. searchResources</code></p>
<p><code>dialogflow.answerrecords.get</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.*</code></p>
<ul>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
</ul>
<p><code>dialogflow.companionAgents.get</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.get</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.get</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.entityTypes.get</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow.examples.get</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.get</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.fulfillments.get</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.get</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.get</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts. get</code></p>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
</ul>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow.pages.get</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.get</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. phoneNumberOrders. get</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.get</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. get</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. get</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.get</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.get</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. get</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.get</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.get</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>CX Premium Conversational Architect
<p>( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p>A Conversational Architect can label conversational data, approve taxonomy changes and design virtual agents for a customer's use cases.</p></td>
<td><p><code>dialogflow.agents.export</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.agents.search</code></p>
<p><code>dialogflow. agents. searchResources</code></p>
<p><code>dialogflow.answerrecords.get</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.*</code></p>
<ul>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
</ul>
<p><code>dialogflow.companionAgents.get</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.get</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.get</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.entityTypes.get</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow.examples.get</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.get</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.fulfillments.get</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.get</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.get</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts. get</code></p>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
</ul>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow.pages.get</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.get</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. phoneNumberOrders. get</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.get</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. get</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. get</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.get</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.get</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. get</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.get</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.get</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>CX Premium Dialog Designer
<p>( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p>A Dialog Designer can label conversational data and propose taxonomy changes for virtual agent modeling.</p></td>
<td><p><code>dialogflow.agents.export</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.agents.search</code></p>
<p><code>dialogflow. agents. searchResources</code></p>
<p><code>dialogflow.answerrecords.get</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.*</code></p>
<ul>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
</ul>
<p><code>dialogflow.companionAgents.get</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.get</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.get</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.entityTypes.get</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow.examples.get</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.get</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.fulfillments.get</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.get</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.get</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts. get</code></p>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
</ul>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow.pages.get</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.get</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. phoneNumberOrders. get</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.get</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. get</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. get</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.get</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.get</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. get</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.get</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.get</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>CX Premium Lead Dialog Designer
<p>( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p>A Dialog Designer Lead can label conversational data and approve taxonomy changes for virtual agent modeling.</p></td>
<td><p><code>dialogflow.agents.export</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.agents.search</code></p>
<p><code>dialogflow. agents. searchResources</code></p>
<p><code>dialogflow.answerrecords.get</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.*</code></p>
<ul>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
</ul>
<p><code>dialogflow.companionAgents.get</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.get</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.get</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.entityTypes.get</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow.examples.get</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.get</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.fulfillments.get</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.get</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.get</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts. get</code></p>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
</ul>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow.pages.get</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.get</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. phoneNumberOrders. get</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.get</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. get</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. get</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.get</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.get</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. get</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.get</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.get</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>CX Premium Viewer
<p>( <code>roles/ dialogflow.aamViewer</code> )</p>
<p>A user can view the taxonomy and data reports in an AAM project.</p></td>
<td><p><code>dialogflow.agents.export</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.agents.search</code></p>
<p><code>dialogflow. agents. searchResources</code></p>
<p><code>dialogflow.answerrecords.get</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.*</code></p>
<ul>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
</ul>
<p><code>dialogflow.companionAgents.get</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.get</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.get</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.entityTypes.get</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow.examples.get</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.get</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.fulfillments.get</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.get</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.get</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts. get</code></p>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
</ul>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow.pages.get</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.get</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. phoneNumberOrders. get</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.get</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. get</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. get</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.get</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.get</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. get</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.get</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.get</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dialogflow Agent Assist Client
<p>( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p>Can create and handle live conversations using Agent Assist features.</p></td>
<td><p><code>dialogflow.answerrecords.*</code></p>
<ul>
<li><code>dialogflow. answerrecords. delete</code></li>
<li><code>dialogflow.answerrecords.get</code></li>
<li><code>dialogflow.answerrecords.list</code></li>
<li><code>dialogflow. answerrecords. update</code></li>
</ul>
<p><code>dialogflow.companionAgents.*</code></p>
<ul>
<li><code>dialogflow. companionAgents. create</code></li>
<li><code>dialogflow. companionAgents. delete</code></li>
<li><code>dialogflow.companionAgents.get</code></li>
<li><code>dialogflow. companionAgents. list</code></li>
<li><code>dialogflow. companionAgents. update</code></li>
</ul>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.*</code></p>
<ul>
<li><code>dialogflow. conversations. addPhoneNumber</code></li>
<li><code>dialogflow. conversations. complete</code></li>
<li><code>dialogflow. conversations. create</code></li>
<li><code>dialogflow.conversations.get</code></li>
<li><code>dialogflow.conversations.list</code></li>
<li><code>dialogflow. conversations. update</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow. interactionMonitoringAlerts.*</code></p>
<ul>
<li><code>dialogflow. interactionMonitoringAlerts. ack</code></li>
<li><code>dialogflow. interactionMonitoringAlerts. get</code></li>
</ul>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.participants.*</code></p>
<ul>
<li><code>dialogflow. participants. analyzeContent</code></li>
<li><code>dialogflow.participants.create</code></li>
<li><code>dialogflow.participants.get</code></li>
<li><code>dialogflow.participants.list</code></li>
<li><code>dialogflow. participants. suggest</code></li>
<li><code>dialogflow.participants.update</code></li>
</ul>
<p><code>dialogflow. sessions. detectIntent</code></p></td>
</tr>
<tr class="odd">
<td>Dialogflow API Client
<p>( <code>roles/ dialogflow.client</code> )</p>
<p>Grant to Dialogflow API clients that perform Dialogflow-specific edits and detect intent calls using the API. Also see <a href="https://docs.cloud.google.com/dialogflow/docs/access-control">Dialogflow access control</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>dialogflow.contexts.*</code></p>
<ul>
<li><code>dialogflow.contexts.create</code></li>
<li><code>dialogflow.contexts.delete</code></li>
<li><code>dialogflow.contexts.get</code></li>
<li><code>dialogflow.contexts.list</code></li>
<li><code>dialogflow.contexts.update</code></li>
</ul>
<p><code>dialogflow.conversations.*</code></p>
<ul>
<li><code>dialogflow. conversations. addPhoneNumber</code></li>
<li><code>dialogflow. conversations. complete</code></li>
<li><code>dialogflow. conversations. create</code></li>
<li><code>dialogflow.conversations.get</code></li>
<li><code>dialogflow.conversations.list</code></li>
<li><code>dialogflow. conversations. update</code></li>
</ul>
<p><code>dialogflow. environments. runContinuousTest</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.participants.*</code></p>
<ul>
<li><code>dialogflow. participants. analyzeContent</code></li>
<li><code>dialogflow.participants.create</code></li>
<li><code>dialogflow.participants.get</code></li>
<li><code>dialogflow.participants.list</code></li>
<li><code>dialogflow. participants. suggest</code></li>
<li><code>dialogflow.participants.update</code></li>
</ul>
<p><code>dialogflow. sessionEntityTypes.*</code></p>
<ul>
<li><code>dialogflow. sessionEntityTypes. create</code></li>
<li><code>dialogflow. sessionEntityTypes. delete</code></li>
<li><code>dialogflow. sessionEntityTypes. get</code></li>
<li><code>dialogflow. sessionEntityTypes. list</code></li>
<li><code>dialogflow. sessionEntityTypes. update</code></li>
</ul>
<p><code>dialogflow.sessions.*</code></p>
<ul>
<li><code>dialogflow. sessions. detectIntent</code></li>
<li><code>dialogflow. sessions. streamingDetectIntent</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Dialogflow Console Agent Editor
<p>( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p>Grant to Dialogflow Console editors that edit existing agents. Also see <a href="https://docs.cloud.google.com/dialogflow/docs/access-control">Dialogflow access control</a> .</p>
<blockquote>
<strong>Caution:</strong> Users with permissions to create or modify Dialogflow agent components, such as tools and webhooks, can configure these components to authenticate as the Dialogflow Service Agent using ID tokens. This capability can be used to interact with other Google Cloud services that accept ID token authentication using the permissions granted to the <a href="https://docs.cloud.google.com/iam/docs/service-agents#dialogflow-service-agent">Dialogflow Service Agent</a> . Carefully control who is granted permissions to configure these Dialogflow agent components.
</blockquote>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>actions.agentVersions.create</code></p>
<p><code>dialogflow.*</code></p>
<ul>
<li><code>dialogflow.agents.create</code></li>
<li><code>dialogflow.agents.delete</code></li>
<li><code>dialogflow.agents.export</code></li>
<li><code>dialogflow.agents.get</code></li>
<li><code>dialogflow.agents.import</code></li>
<li><code>dialogflow.agents.list</code></li>
<li><code>dialogflow.agents.restore</code></li>
<li><code>dialogflow.agents.search</code></li>
<li><code>dialogflow. agents. searchResources</code></li>
<li><code>dialogflow.agents.train</code></li>
<li><code>dialogflow.agents.update</code></li>
<li><code>dialogflow.agents.validate</code></li>
<li><code>dialogflow. answerrecords. delete</code></li>
<li><code>dialogflow.answerrecords.get</code></li>
<li><code>dialogflow.answerrecords.list</code></li>
<li><code>dialogflow. answerrecords. update</code></li>
<li><code>dialogflow.callMatchers.create</code></li>
<li><code>dialogflow.callMatchers.delete</code></li>
<li><code>dialogflow.callMatchers.list</code></li>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
<li><code>dialogflow. companionAgents. create</code></li>
<li><code>dialogflow. companionAgents. delete</code></li>
<li><code>dialogflow.companionAgents.get</code></li>
<li><code>dialogflow. companionAgents. list</code></li>
<li><code>dialogflow. companionAgents. update</code></li>
<li><code>dialogflow.contexts.create</code></li>
<li><code>dialogflow.contexts.delete</code></li>
<li><code>dialogflow.contexts.get</code></li>
<li><code>dialogflow.contexts.list</code></li>
<li><code>dialogflow.contexts.update</code></li>
<li><code>dialogflow. conversationDatasets. create</code></li>
<li><code>dialogflow. conversationDatasets. delete</code></li>
<li><code>dialogflow. conversationDatasets. get</code></li>
<li><code>dialogflow. conversationDatasets. import</code></li>
<li><code>dialogflow. conversationDatasets. list</code></li>
<li><code>dialogflow. conversationModels. create</code></li>
<li><code>dialogflow. conversationModels. delete</code></li>
<li><code>dialogflow. conversationModels. deploy</code></li>
<li><code>dialogflow. conversationModels. get</code></li>
<li><code>dialogflow. conversationModels. list</code></li>
<li><code>dialogflow. conversationModels. undeploy</code></li>
<li><code>dialogflow. conversationProfiles. create</code></li>
<li><code>dialogflow. conversationProfiles. delete</code></li>
<li><code>dialogflow. conversationProfiles. get</code></li>
<li><code>dialogflow. conversationProfiles. list</code></li>
<li><code>dialogflow. conversationProfiles. update</code></li>
<li><code>dialogflow. conversations. addPhoneNumber</code></li>
<li><code>dialogflow. conversations. complete</code></li>
<li><code>dialogflow. conversations. create</code></li>
<li><code>dialogflow.conversations.get</code></li>
<li><code>dialogflow.conversations.list</code></li>
<li><code>dialogflow. conversations. update</code></li>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
<li><code>dialogflow.documents.create</code></li>
<li><code>dialogflow.documents.delete</code></li>
<li><code>dialogflow.documents.get</code></li>
<li><code>dialogflow.documents.list</code></li>
<li><code>dialogflow.encryptionspec.get</code></li>
<li><code>dialogflow. encryptionspec. update</code></li>
<li><code>dialogflow.entityTypes.create</code></li>
<li><code>dialogflow. entityTypes. createEntity</code></li>
<li><code>dialogflow.entityTypes.delete</code></li>
<li><code>dialogflow. entityTypes. deleteEntity</code></li>
<li><code>dialogflow.entityTypes.get</code></li>
<li><code>dialogflow.entityTypes.list</code></li>
<li><code>dialogflow.entityTypes.update</code></li>
<li><code>dialogflow. entityTypes. updateEntity</code></li>
<li><code>dialogflow.environments.create</code></li>
<li><code>dialogflow.environments.delete</code></li>
<li><code>dialogflow.environments.get</code></li>
<li><code>dialogflow. environments. getHistory</code></li>
<li><code>dialogflow.environments.list</code></li>
<li><code>dialogflow. environments. lookupHistory</code></li>
<li><code>dialogflow. environments. runContinuousTest</code></li>
<li><code>dialogflow.environments.update</code></li>
<li><code>dialogflow.examples.create</code></li>
<li><code>dialogflow.examples.delete</code></li>
<li><code>dialogflow.examples.get</code></li>
<li><code>dialogflow.examples.list</code></li>
<li><code>dialogflow.examples.update</code></li>
<li><code>dialogflow.experiments.create</code></li>
<li><code>dialogflow.experiments.delete</code></li>
<li><code>dialogflow.experiments.get</code></li>
<li><code>dialogflow.experiments.list</code></li>
<li><code>dialogflow.experiments.update</code></li>
<li><code>dialogflow.flows.create</code></li>
<li><code>dialogflow.flows.delete</code></li>
<li><code>dialogflow.flows.get</code></li>
<li><code>dialogflow.flows.list</code></li>
<li><code>dialogflow.flows.train</code></li>
<li><code>dialogflow.flows.update</code></li>
<li><code>dialogflow.flows.validate</code></li>
<li><code>dialogflow.fulfillments.get</code></li>
<li><code>dialogflow.fulfillments.update</code></li>
<li><code>dialogflow.generators.create</code></li>
<li><code>dialogflow.generators.delete</code></li>
<li><code>dialogflow.generators.get</code></li>
<li><code>dialogflow.generators.list</code></li>
<li><code>dialogflow.generators.update</code></li>
<li><code>dialogflow.integrations.create</code></li>
<li><code>dialogflow.integrations.delete</code></li>
<li><code>dialogflow.integrations.get</code></li>
<li><code>dialogflow.integrations.list</code></li>
<li><code>dialogflow.integrations.update</code></li>
<li><code>dialogflow.intents.create</code></li>
<li><code>dialogflow.intents.delete</code></li>
<li><code>dialogflow.intents.get</code></li>
<li><code>dialogflow.intents.list</code></li>
<li><code>dialogflow.intents.update</code></li>
<li><code>dialogflow. interactionMonitoringAlerts. ack</code></li>
<li><code>dialogflow. interactionMonitoringAlerts. get</code></li>
<li><code>dialogflow. knowledgeBases. create</code></li>
<li><code>dialogflow. knowledgeBases. delete</code></li>
<li><code>dialogflow.knowledgeBases.get</code></li>
<li><code>dialogflow.knowledgeBases.list</code></li>
<li><code>dialogflow. knowledgeBases. update</code></li>
<li><code>dialogflow.messages.list</code></li>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
<li><code>dialogflow.operations.get</code></li>
<li><code>dialogflow.pages.create</code></li>
<li><code>dialogflow.pages.delete</code></li>
<li><code>dialogflow.pages.get</code></li>
<li><code>dialogflow.pages.list</code></li>
<li><code>dialogflow.pages.update</code></li>
<li><code>dialogflow. participants. analyzeContent</code></li>
<li><code>dialogflow.participants.create</code></li>
<li><code>dialogflow.participants.get</code></li>
<li><code>dialogflow.participants.list</code></li>
<li><code>dialogflow. participants. suggest</code></li>
<li><code>dialogflow.participants.update</code></li>
<li><code>dialogflow. phoneNumberOrders. cancel</code></li>
<li><code>dialogflow. phoneNumberOrders. create</code></li>
<li><code>dialogflow. phoneNumberOrders. get</code></li>
<li><code>dialogflow. phoneNumberOrders. list</code></li>
<li><code>dialogflow. phoneNumberOrders. update</code></li>
<li><code>dialogflow.phoneNumbers.delete</code></li>
<li><code>dialogflow.phoneNumbers.list</code></li>
<li><code>dialogflow. phoneNumbers. undelete</code></li>
<li><code>dialogflow.phoneNumbers.update</code></li>
<li><code>dialogflow.playbooks.create</code></li>
<li><code>dialogflow.playbooks.delete</code></li>
<li><code>dialogflow.playbooks.get</code></li>
<li><code>dialogflow.playbooks.list</code></li>
<li><code>dialogflow.playbooks.update</code></li>
<li><code>dialogflow. securitySettings. create</code></li>
<li><code>dialogflow. securitySettings. delete</code></li>
<li><code>dialogflow. securitySettings. get</code></li>
<li><code>dialogflow. securitySettings. list</code></li>
<li><code>dialogflow. securitySettings. update</code></li>
<li><code>dialogflow. sessionEntityTypes. create</code></li>
<li><code>dialogflow. sessionEntityTypes. delete</code></li>
<li><code>dialogflow. sessionEntityTypes. get</code></li>
<li><code>dialogflow. sessionEntityTypes. list</code></li>
<li><code>dialogflow. sessionEntityTypes. update</code></li>
<li><code>dialogflow. sessions. detectIntent</code></li>
<li><code>dialogflow. sessions. streamingDetectIntent</code></li>
<li><code>dialogflow. smartMessagingEntries. create</code></li>
<li><code>dialogflow. smartMessagingEntries. delete</code></li>
<li><code>dialogflow. smartMessagingEntries. get</code></li>
<li><code>dialogflow. smartMessagingEntries. list</code></li>
<li><code>dialogflow. testcases. calculateCoverage</code></li>
<li><code>dialogflow.testcases.create</code></li>
<li><code>dialogflow.testcases.delete</code></li>
<li><code>dialogflow.testcases.export</code></li>
<li><code>dialogflow.testcases.get</code></li>
<li><code>dialogflow.testcases.import</code></li>
<li><code>dialogflow.testcases.list</code></li>
<li><code>dialogflow.testcases.run</code></li>
<li><code>dialogflow.testcases.update</code></li>
<li><code>dialogflow.tools.create</code></li>
<li><code>dialogflow.tools.delete</code></li>
<li><code>dialogflow.tools.get</code></li>
<li><code>dialogflow.tools.list</code></li>
<li><code>dialogflow.tools.update</code></li>
<li><code>dialogflow. transitionRouteGroups. create</code></li>
<li><code>dialogflow. transitionRouteGroups. delete</code></li>
<li><code>dialogflow. transitionRouteGroups. get</code></li>
<li><code>dialogflow. transitionRouteGroups. list</code></li>
<li><code>dialogflow. transitionRouteGroups. update</code></li>
<li><code>dialogflow.versions.create</code></li>
<li><code>dialogflow.versions.delete</code></li>
<li><code>dialogflow.versions.get</code></li>
<li><code>dialogflow.versions.list</code></li>
<li><code>dialogflow.versions.load</code></li>
<li><code>dialogflow.versions.update</code></li>
<li><code>dialogflow.webhooks.create</code></li>
<li><code>dialogflow.webhooks.delete</code></li>
<li><code>dialogflow.webhooks.get</code></li>
<li><code>dialogflow.webhooks.list</code></li>
<li><code>dialogflow.webhooks.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td>Dialogflow Console Simulator User
<p>( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p>Can perform query of dialogflow suggestions in the simulator in web console.</p></td>
<td><p><code>dialogflow.companionAgents.*</code></p>
<ul>
<li><code>dialogflow. companionAgents. create</code></li>
<li><code>dialogflow. companionAgents. delete</code></li>
<li><code>dialogflow.companionAgents.get</code></li>
<li><code>dialogflow. companionAgents. list</code></li>
<li><code>dialogflow. companionAgents. update</code></li>
</ul>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.*</code></p>
<ul>
<li><code>dialogflow. conversations. addPhoneNumber</code></li>
<li><code>dialogflow. conversations. complete</code></li>
<li><code>dialogflow. conversations. create</code></li>
<li><code>dialogflow.conversations.get</code></li>
<li><code>dialogflow.conversations.list</code></li>
<li><code>dialogflow. conversations. update</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts.*</code></p>
<ul>
<li><code>dialogflow. interactionMonitoringAlerts. ack</code></li>
<li><code>dialogflow. interactionMonitoringAlerts. get</code></li>
</ul>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.participants.*</code></p>
<ul>
<li><code>dialogflow. participants. analyzeContent</code></li>
<li><code>dialogflow.participants.create</code></li>
<li><code>dialogflow.participants.get</code></li>
<li><code>dialogflow.participants.list</code></li>
<li><code>dialogflow. participants. suggest</code></li>
<li><code>dialogflow.participants.update</code></li>
</ul>
<p><code>dialogflow. sessions. detectIntent</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dialogflow Console Smart Messaging Allowlist Editor
<p>( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p>Can edit allowlist for smart messaging associated with conversation model in the agent assist console</p></td>
<td><p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow. smartMessagingEntries.*</code></p>
<ul>
<li><code>dialogflow. smartMessagingEntries. create</code></li>
<li><code>dialogflow. smartMessagingEntries. delete</code></li>
<li><code>dialogflow. smartMessagingEntries. get</code></li>
<li><code>dialogflow. smartMessagingEntries. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dialogflow Conversation Manager
<p>( <code>roles/ dialogflow.conversationManager</code> )</p>
<p>Can manage all the resources related to Dialogflow Conversations.</p></td>
<td><p><code>dialogflow. conversationProfiles.*</code></p>
<ul>
<li><code>dialogflow. conversationProfiles. create</code></li>
<li><code>dialogflow. conversationProfiles. delete</code></li>
<li><code>dialogflow. conversationProfiles. get</code></li>
<li><code>dialogflow. conversationProfiles. list</code></li>
<li><code>dialogflow. conversationProfiles. update</code></li>
</ul>
<p><code>dialogflow.conversations.*</code></p>
<ul>
<li><code>dialogflow. conversations. addPhoneNumber</code></li>
<li><code>dialogflow. conversations. complete</code></li>
<li><code>dialogflow. conversations. create</code></li>
<li><code>dialogflow.conversations.get</code></li>
<li><code>dialogflow.conversations.list</code></li>
<li><code>dialogflow. conversations. update</code></li>
</ul>
<p><code>dialogflow.participants.*</code></p>
<ul>
<li><code>dialogflow. participants. analyzeContent</code></li>
<li><code>dialogflow.participants.create</code></li>
<li><code>dialogflow.participants.get</code></li>
<li><code>dialogflow.participants.list</code></li>
<li><code>dialogflow. participants. suggest</code></li>
<li><code>dialogflow.participants.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Dialogflow Entity Type Admin
<p>( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p>Can read &amp; write entity types.</p></td>
<td><p><code>dialogflow.entityTypes.*</code></p>
<ul>
<li><code>dialogflow.entityTypes.create</code></li>
<li><code>dialogflow. entityTypes. createEntity</code></li>
<li><code>dialogflow.entityTypes.delete</code></li>
<li><code>dialogflow. entityTypes. deleteEntity</code></li>
<li><code>dialogflow.entityTypes.get</code></li>
<li><code>dialogflow.entityTypes.list</code></li>
<li><code>dialogflow.entityTypes.update</code></li>
<li><code>dialogflow. entityTypes. updateEntity</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Dialogflow Environment editor
<p>( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p>Can read &amp; update environment and its sub-resources.</p></td>
<td><p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow. environments. getHistory</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow. environments. lookupHistory</code></p>
<p><code>dialogflow. environments. runContinuousTest</code></p>
<p><code>dialogflow.environments.update</code></p>
<p><code>dialogflow.experiments.*</code></p>
<ul>
<li><code>dialogflow.experiments.create</code></li>
<li><code>dialogflow.experiments.delete</code></li>
<li><code>dialogflow.experiments.get</code></li>
<li><code>dialogflow.experiments.list</code></li>
<li><code>dialogflow.experiments.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Dialogflow Flow editor
<p>( <code>roles/ dialogflow.flowEditor</code> )</p>
<p>Can read &amp; update flow and its sub-resources.</p></td>
<td><p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.flows.train</code></p>
<p><code>dialogflow.flows.update</code></p>
<p><code>dialogflow.flows.validate</code></p>
<p><code>dialogflow.pages.*</code></p>
<ul>
<li><code>dialogflow.pages.create</code></li>
<li><code>dialogflow.pages.delete</code></li>
<li><code>dialogflow.pages.get</code></li>
<li><code>dialogflow.pages.list</code></li>
<li><code>dialogflow.pages.update</code></li>
</ul>
<p><code>dialogflow. transitionRouteGroups.*</code></p>
<ul>
<li><code>dialogflow. transitionRouteGroups. create</code></li>
<li><code>dialogflow. transitionRouteGroups. delete</code></li>
<li><code>dialogflow. transitionRouteGroups. get</code></li>
<li><code>dialogflow. transitionRouteGroups. list</code></li>
<li><code>dialogflow. transitionRouteGroups. update</code></li>
</ul>
<p><code>dialogflow.versions.*</code></p>
<ul>
<li><code>dialogflow.versions.create</code></li>
<li><code>dialogflow.versions.delete</code></li>
<li><code>dialogflow.versions.get</code></li>
<li><code>dialogflow.versions.list</code></li>
<li><code>dialogflow.versions.load</code></li>
<li><code>dialogflow.versions.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Dialogflow Integration Manager
<p>( <code>roles/ dialogflow.integrationManager</code> )</p>
<p>Can add, remove, enable and disable Dialogflow integrations.</p></td>
<td><p><code>dialogflow.integrations.*</code></p>
<ul>
<li><code>dialogflow.integrations.create</code></li>
<li><code>dialogflow.integrations.delete</code></li>
<li><code>dialogflow.integrations.get</code></li>
<li><code>dialogflow.integrations.list</code></li>
<li><code>dialogflow.integrations.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Dialogflow Intent Admin
<p>( <code>roles/ dialogflow.intentAdmin</code> )</p>
<p>Can read &amp; write intents.</p></td>
<td><p><code>dialogflow.intents.*</code></p>
<ul>
<li><code>dialogflow.intents.create</code></li>
<li><code>dialogflow.intents.delete</code></li>
<li><code>dialogflow.intents.get</code></li>
<li><code>dialogflow.intents.list</code></li>
<li><code>dialogflow.intents.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Dialogflow API Reader
<p>( <code>roles/ dialogflow.reader</code> )</p>
<p>Grant to Dialogflow API clients that perform Dialogflow-specific read-only calls using the API. Also see <a href="https://docs.cloud.google.com/dialogflow/docs/access-control">Dialogflow access control</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>dialogflow.agents.export</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.agents.search</code></p>
<p><code>dialogflow. agents. searchResources</code></p>
<p><code>dialogflow.answerrecords.get</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.*</code></p>
<ul>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
</ul>
<p><code>dialogflow.companionAgents.get</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.get</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. get</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.get</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.entityTypes.get</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow.examples.get</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.get</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.fulfillments.get</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.get</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.get</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts. get</code></p>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
</ul>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow.pages.get</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.get</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. phoneNumberOrders. get</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.get</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. get</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. get</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.get</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.get</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. get</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.get</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.get</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Dialogflow Test Case Admin
<p>( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p>Can read &amp; write test cases.</p></td>
<td><p><code>dialogflow.testcases.*</code></p>
<ul>
<li><code>dialogflow. testcases. calculateCoverage</code></li>
<li><code>dialogflow.testcases.create</code></li>
<li><code>dialogflow.testcases.delete</code></li>
<li><code>dialogflow.testcases.export</code></li>
<li><code>dialogflow.testcases.get</code></li>
<li><code>dialogflow.testcases.import</code></li>
<li><code>dialogflow.testcases.list</code></li>
<li><code>dialogflow.testcases.run</code></li>
<li><code>dialogflow.testcases.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Dialogflow Webhook Admin
<p>( <code>roles/ dialogflow.webhookAdmin</code> )</p>
<p>Can read &amp; write webhooks.</p>
<blockquote>
<strong>Caution:</strong> Users with permissions to create or modify Dialogflow agent components, such as tools and webhooks, can configure these components to authenticate as the Dialogflow Service Agent using ID tokens. This capability can be used to interact with other Google Cloud services that accept ID token authentication using the permissions granted to the <a href="https://docs.cloud.google.com/iam/docs/service-agents#dialogflow-service-agent">Dialogflow Service Agent</a> . Carefully control who is granted permissions to configure these Dialogflow agent components.
</blockquote></td>
<td><p><code>dialogflow.webhooks.*</code></p>
<ul>
<li><code>dialogflow.webhooks.create</code></li>
<li><code>dialogflow.webhooks.delete</code></li>
<li><code>dialogflow.webhooks.get</code></li>
<li><code>dialogflow.webhooks.list</code></li>
<li><code>dialogflow.webhooks.update</code></li>
</ul></td>
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
<td>Dialogflow Service Agent
<p>( <code>roles/ dialogflow.serviceAgent</code> )</p>
<p>Gives Dialogflow Service Account access to resources on behalf of user project for Integrations (Facebook Messenger, Slack, Telephony, etc.), BigQuery, Discovery Engine, Integration Connectors, Application Integration, and Vertex.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.endpoints.get</code></p>
<p><code>aiplatform.endpoints.predict</code></p>
<p><code>aiplatform.extensions.execute</code></p>
<p><code>aiplatform.extensions.get</code></p>
<p><code>aiplatform.models.get</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>ces.apps.get</code></p>
<p><code>ces.sessions.*</code></p>
<ul>
<li><code>ces.sessions.bidiRunSession</code></li>
<li><code>ces.sessions.runSession</code></li>
</ul>
<p><code>ces.tools.execute</code></p>
<p><code>ces.tools.get</code></p>
<p><code>ces.toolsets.get</code></p>
<p><code>cloudfunctions. functions. invoke</code></p>
<p><code>connectors.actions.*</code></p>
<ul>
<li><code>connectors.actions.execute</code></li>
<li><code>connectors.actions.list</code></li>
</ul>
<p><code>connectors. connections. executeSqlQuery</code></p>
<p><code>connectors. connections. generateOpenAPISpec</code></p>
<p><code>connectors.connections.get</code></p>
<p><code>connectors.entities.*</code></p>
<ul>
<li><code>connectors.entities.create</code></li>
<li><code>connectors.entities.delete</code></li>
<li><code>connectors. entities. deleteEntitiesWithConditions</code></li>
<li><code>connectors.entities.get</code></li>
<li><code>connectors.entities.list</code></li>
<li><code>connectors.entities.update</code></li>
<li><code>connectors. entities. updateEntitiesWithConditions</code></li>
</ul>
<p><code>connectors.entityTypes.list</code></p>
<p><code>connectors.operations.get</code></p>
<p><code>connectors.versions.get</code></p>
<p><code>dialogflow.agents.export</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.agents.search</code></p>
<p><code>dialogflow. agents. searchResources</code></p>
<p><code>dialogflow.answerrecords.get</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.*</code></p>
<ul>
<li><code>dialogflow.changelogs.get</code></li>
<li><code>dialogflow.changelogs.list</code></li>
</ul>
<p><code>dialogflow.companionAgents.get</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.*</code></p>
<ul>
<li><code>dialogflow.contexts.create</code></li>
<li><code>dialogflow.contexts.delete</code></li>
<li><code>dialogflow.contexts.get</code></li>
<li><code>dialogflow.contexts.list</code></li>
<li><code>dialogflow.contexts.update</code></li>
</ul>
<p><code>dialogflow. conversationDatasets. get</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. get</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles.*</code></p>
<ul>
<li><code>dialogflow. conversationProfiles. create</code></li>
<li><code>dialogflow. conversationProfiles. delete</code></li>
<li><code>dialogflow. conversationProfiles. get</code></li>
<li><code>dialogflow. conversationProfiles. list</code></li>
<li><code>dialogflow. conversationProfiles. update</code></li>
</ul>
<p><code>dialogflow.conversations.*</code></p>
<ul>
<li><code>dialogflow. conversations. addPhoneNumber</code></li>
<li><code>dialogflow. conversations. complete</code></li>
<li><code>dialogflow. conversations. create</code></li>
<li><code>dialogflow.conversations.get</code></li>
<li><code>dialogflow.conversations.list</code></li>
<li><code>dialogflow. conversations. update</code></li>
</ul>
<p><code>dialogflow.deployments.*</code></p>
<ul>
<li><code>dialogflow.deployments.get</code></li>
<li><code>dialogflow.deployments.list</code></li>
</ul>
<p><code>dialogflow.documents.get</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.entityTypes.get</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.get</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow. environments. runContinuousTest</code></p>
<p><code>dialogflow.examples.get</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.get</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.fulfillments.get</code></p>
<p><code>dialogflow.generators.get</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.get</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.get</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow. interactionMonitoringAlerts. get</code></p>
<p><code>dialogflow.knowledgeBases.get</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code>dialogflow. modelEvaluations. get</code></li>
<li><code>dialogflow. modelEvaluations. list</code></li>
</ul>
<p><code>dialogflow.operations.get</code></p>
<p><code>dialogflow.pages.get</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.*</code></p>
<ul>
<li><code>dialogflow. participants. analyzeContent</code></li>
<li><code>dialogflow.participants.create</code></li>
<li><code>dialogflow.participants.get</code></li>
<li><code>dialogflow.participants.list</code></li>
<li><code>dialogflow. participants. suggest</code></li>
<li><code>dialogflow.participants.update</code></li>
</ul>
<p><code>dialogflow. phoneNumberOrders. get</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.get</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes.*</code></p>
<ul>
<li><code>dialogflow. sessionEntityTypes. create</code></li>
<li><code>dialogflow. sessionEntityTypes. delete</code></li>
<li><code>dialogflow. sessionEntityTypes. get</code></li>
<li><code>dialogflow. sessionEntityTypes. list</code></li>
<li><code>dialogflow. sessionEntityTypes. update</code></li>
</ul>
<p><code>dialogflow.sessions.*</code></p>
<ul>
<li><code>dialogflow. sessions. detectIntent</code></li>
<li><code>dialogflow. sessions. streamingDetectIntent</code></li>
</ul>
<p><code>dialogflow. smartMessagingEntries. get</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.get</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.get</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. get</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.get</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.get</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>discoveryengine. collections. get</code></p>
<p><code>discoveryengine. collections. list</code></p>
<p><code>discoveryengine. dataStores. create</code></p>
<p><code>discoveryengine.dataStores.get</code></p>
<p><code>discoveryengine. dataStores. list</code></p>
<p><code>discoveryengine. documents. create</code></p>
<p><code>discoveryengine.documents.get</code></p>
<p><code>discoveryengine. documents. import</code></p>
<p><code>discoveryengine.documents.list</code></p>
<p><code>discoveryengine. documents. update</code></p>
<p><code>discoveryengine.engines.create</code></p>
<p><code>discoveryengine.engines.delete</code></p>
<p><code>discoveryengine.engines.get</code></p>
<p><code>discoveryengine.engines.update</code></p>
<p><code>discoveryengine.schemas.get</code></p>
<p><code>discoveryengine.schemas.list</code></p>
<p><code>discoveryengine. servingConfigs. search</code></p>
<p><code>dlp.deidentifyTemplates.get</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.inspectTemplates.get</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrations. generateOpenApiSpec</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>pubsub.snapshots.seek</code></p>
<p><code>pubsub.subscriptions.consume</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.jobs.run</code></p>
<p><code>run.routes.invoke</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>speakerid.phrases.*</code></p>
<ul>
<li><code>speakerid.phrases.create</code></li>
<li><code>speakerid.phrases.delete</code></li>
<li><code>speakerid.phrases.get</code></li>
<li><code>speakerid.phrases.list</code></li>
</ul>
<p><code>speakerid.speakers.*</code></p>
<ul>
<li><code>speakerid.speakers.create</code></li>
<li><code>speakerid.speakers.delete</code></li>
<li><code>speakerid.speakers.get</code></li>
<li><code>speakerid.speakers.list</code></li>
<li><code>speakerid.speakers.verify</code></li>
</ul>
<p><code>speech.adaptations.execute</code></p>
<p><code>speech.customClasses.get</code></p>
<p><code>speech.customClasses.list</code></p>
<p><code>speech.phraseSets.get</code></p>
<p><code>speech.phraseSets.list</code></p>
<p><code>speech.recognizers.get</code></p>
<p><code>speech.recognizers.list</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Dialogflow permissions

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
<td><code>dialogflow.agents.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.agents.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.agents.export</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.agents.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.agents.import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.agents.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.agents.restore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.agents.search</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. agents. searchResources</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.agents.train</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.agents.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.agents.validate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. answerrecords. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.answerrecords.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.answerrecords.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. answerrecords. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.callMatchers.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.callMatchers.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.callMatchers.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.changelogs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.changelogs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. companionAgents. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. companionAgents. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.companionAgents.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. companionAgents. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. companionAgents. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.contexts.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.contexts.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.contexts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.contexts.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.contexts.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversationDatasets. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversationDatasets. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversationDatasets. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversationDatasets. import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversationDatasets. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversationModels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversationModels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversationModels. deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversationModels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversationModels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversationModels. undeploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversationProfiles. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversationProfiles. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversationProfiles. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversationProfiles. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversationProfiles. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversations. addPhoneNumber</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversations. complete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. conversations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.conversations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.conversations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. conversations. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.deployments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.deployments.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.documents.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.documents.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.documents.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.documents.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.encryptionspec.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. encryptionspec. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.entityTypes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. entityTypes. createEntity</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.entityTypes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. entityTypes. deleteEntity</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.entityTypes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.entityTypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.entityTypes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. entityTypes. updateEntity</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code>roles/ dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.environments.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.environments.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.environments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. environments. getHistory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.environments.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. environments. lookupHistory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. environments. runContinuousTest</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.environments.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.examples.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.examples.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.examples.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.examples.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.examples.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.experiments.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.experiments.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.experiments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.experiments.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.experiments.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code>roles/ dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.flows.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.flows.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.flows.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.flows.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.flows.train</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.flows.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.flows.validate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.fulfillments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.fulfillments.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.generators.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.generators.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.generators.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.generators.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.generators.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.integrations.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code>roles/ dialogflow.integrationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.integrations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code>roles/ dialogflow.integrationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.integrations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code>roles/ dialogflow.integrationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.integrations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code>roles/ dialogflow.integrationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.integrations.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code>roles/ dialogflow.integrationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.intents.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code>roles/ dialogflow.intentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.intents.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code>roles/ dialogflow.intentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.intents.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code>roles/ dialogflow.intentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.intents.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code>roles/ dialogflow.intentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.intents.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code>roles/ dialogflow.intentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. interactionMonitoringAlerts. ack</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. interactionMonitoringAlerts. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. knowledgeBases. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. knowledgeBases. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.knowledgeBases.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.knowledgeBases.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. knowledgeBases. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.messages.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. modelEvaluations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. modelEvaluations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.pages.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.pages.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.pages.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.pages.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.pages.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. participants. analyzeContent</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.participants.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.participants.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.participants.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. participants. suggest</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.participants.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code>roles/ dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. phoneNumberOrders. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. phoneNumberOrders. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. phoneNumberOrders. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. phoneNumberOrders. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. phoneNumberOrders. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.phoneNumbers.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.phoneNumbers.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. phoneNumbers. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.phoneNumbers.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.playbooks.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.playbooks.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.playbooks.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.playbooks.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.playbooks.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. securitySettings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. securitySettings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. securitySettings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. securitySettings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. securitySettings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. sessionEntityTypes. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. sessionEntityTypes. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. sessionEntityTypes. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. sessionEntityTypes. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. sessionEntityTypes. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. sessions. detectIntent</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code>roles/ dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. sessions. streamingDetectIntent</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code>roles/ dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. smartMessagingEntries. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. smartMessagingEntries. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. smartMessagingEntries. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. smartMessagingEntries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. testcases. calculateCoverage</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.testcases.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.testcases.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.testcases.export</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.testcases.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.testcases.import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.testcases.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.testcases.run</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.testcases.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code>roles/ dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.tools.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.tools.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.tools.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.tools.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.tools.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. transitionRouteGroups. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow. transitionRouteGroups. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow. transitionRouteGroups. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow. transitionRouteGroups. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow. transitionRouteGroups. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.versions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.versions.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.versions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.versions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.versions.load</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.versions.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code>roles/ dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.webhooks.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code>roles/ dialogflow.webhookAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dialogflow.webhooks.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code>roles/ dialogflow.webhookAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dialogflow.webhooks.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code>roles/ dialogflow.webhookAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dialogflow.webhooks.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code>roles/ dialogflow.webhookAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dialogflow.webhooks.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code>roles/ dialogflow.webhookAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
