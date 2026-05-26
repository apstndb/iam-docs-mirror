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
<td><h4 id="dialogflow.admin" class="role-title add-link" data-text="Dialogflow API Admin" tabindex="-1">Dialogflow API Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p>Grant to Dialogflow API admins that need full access to Dialogflow-specific resources. Also see <a href="https://docs.cloud.google.com/dialogflow/docs/access-control">Dialogflow access control</a> .</p>
<blockquote>
<strong>Caution:</strong> Users with permissions to create or modify Dialogflow agent components, such as tools and webhooks, can configure these components to authenticate as the Dialogflow Service Agent using ID tokens. This capability can be used to interact with other Google Cloud services that accept ID token authentication using the permissions granted to the <a href="https://docs.cloud.google.com/iam/docs/service-agents#dialogflow-service-agent">Dialogflow Service Agent</a> . Carefully control who is granted permissions to configure these Dialogflow agent components.
</blockquote>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">dialogflow.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.agents.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.export</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.import</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.restore</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.search</code></li>
<li><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.train</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.validate</code></li>
<li><code dir="ltr" translate="no">dialogflow.  answerrecords.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  answerrecords.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.callMatchers.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.callMatchers.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  import</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  deploy</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  undeploy</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  addPhoneNumber</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  complete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.documents.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.documents.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.documents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.documents.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  encryptionspec.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  createEntity</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  deleteEntity</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  updateEntity</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  environments.  getHistory</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  environments.  lookupHistory</code></li>
<li><code dir="ltr" translate="no">dialogflow.  environments.  runContinuousTest</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.train</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.validate</code></li>
<li><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.fulfillments.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  ack</code></li>
<li><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.messages.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.operations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  analyzeContent</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  cancel</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.phoneNumbers.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumbers.  undelete</code></li>
<li><code dir="ltr" translate="no">dialogflow.phoneNumbers.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessions.  detectIntent</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessions.  streamingDetectIntent</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  testcases.  calculateCoverage</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.export</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.import</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.run</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.load</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.viewer" class="role-title add-link" data-text="Dialogflow Viewer" tabindex="-1">Dialogflow Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p>Viewer role for dialogflow</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.agents.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.search</code></p>
<p><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  environments.  getHistory</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  environments.  lookupHistory</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  testcases.  calculateCoverage</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.aamAdmin" class="role-title add-link" data-text="CX Premium Admin" tabindex="-1">CX Premium Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p>An admin has access to all resources and can perform all administrative actions in an AAM project.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.agents.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.search</code></p>
<p><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.aamConversationalArchitect" class="role-title add-link" data-text="CX Premium Conversational Architect" tabindex="-1">CX Premium Conversational Architect</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p>A Conversational Architect can label conversational data, approve taxonomy changes and design virtual agents for a customer's use cases.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.agents.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.search</code></p>
<p><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.aamDialogDesigner" class="role-title add-link" data-text="CX Premium Dialog Designer" tabindex="-1">CX Premium Dialog Designer</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p>A Dialog Designer can label conversational data and propose taxonomy changes for virtual agent modeling.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.agents.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.search</code></p>
<p><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.aamLeadDialogDesigner" class="role-title add-link" data-text="CX Premium Lead Dialog Designer" tabindex="-1">CX Premium Lead Dialog Designer</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p>A Dialog Designer Lead can label conversational data and approve taxonomy changes for virtual agent modeling.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.agents.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.search</code></p>
<p><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.aamViewer" class="role-title add-link" data-text="CX Premium Viewer" tabindex="-1">CX Premium Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p>A user can view the taxonomy and data reports in an AAM project.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.agents.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.search</code></p>
<p><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.agentAssistClient" class="role-title add-link" data-text="Dialogflow Agent Assist Client" tabindex="-1">Dialogflow Agent Assist Client</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p>Can create and handle live conversations using Agent Assist features.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.answerrecords.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  answerrecords.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  answerrecords.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  addPhoneNumber</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  complete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  ack</code></li>
<li><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  participants.  analyzeContent</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  sessions.  detectIntent</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.client" class="role-title add-link" data-text="Dialogflow API Client" tabindex="-1">Dialogflow API Client</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p>Grant to Dialogflow API clients that perform Dialogflow-specific edits and detect intent calls using the API. Also see <a href="https://docs.cloud.google.com/dialogflow/docs/access-control">Dialogflow access control</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">dialogflow.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.contexts.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.conversations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  addPhoneNumber</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  complete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  environments.  runContinuousTest</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  participants.  analyzeContent</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  sessions.  detectIntent</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessions.  streamingDetectIntent</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.consoleAgentEditor" class="role-title add-link" data-text="Dialogflow Console Agent Editor" tabindex="-1">Dialogflow Console Agent Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Grant to Dialogflow Console editors that edit existing agents. Also see <a href="https://docs.cloud.google.com/dialogflow/docs/access-control">Dialogflow access control</a> .</p>
<blockquote>
<strong>Caution:</strong> Users with permissions to create or modify Dialogflow agent components, such as tools and webhooks, can configure these components to authenticate as the Dialogflow Service Agent using ID tokens. This capability can be used to interact with other Google Cloud services that accept ID token authentication using the permissions granted to the <a href="https://docs.cloud.google.com/iam/docs/service-agents#dialogflow-service-agent">Dialogflow Service Agent</a> . Carefully control who is granted permissions to configure these Dialogflow agent components.
</blockquote>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">actions.agentVersions.create</code></p>
<p><code dir="ltr" translate="no">dialogflow.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.agents.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.export</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.import</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.restore</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.search</code></li>
<li><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.train</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.agents.validate</code></li>
<li><code dir="ltr" translate="no">dialogflow.  answerrecords.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  answerrecords.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.callMatchers.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.callMatchers.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  import</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  deploy</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationModels.  undeploy</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  addPhoneNumber</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  complete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.documents.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.documents.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.documents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.documents.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  encryptionspec.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  createEntity</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  deleteEntity</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  updateEntity</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  environments.  getHistory</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  environments.  lookupHistory</code></li>
<li><code dir="ltr" translate="no">dialogflow.  environments.  runContinuousTest</code></li>
<li><code dir="ltr" translate="no">dialogflow.environments.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.examples.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.train</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.flows.validate</code></li>
<li><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.fulfillments.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.generators.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  ack</code></li>
<li><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.messages.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.operations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  analyzeContent</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  cancel</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.phoneNumbers.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  phoneNumbers.  undelete</code></li>
<li><code dir="ltr" translate="no">dialogflow.phoneNumbers.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.playbooks.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  securitySettings.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessions.  detectIntent</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessions.  streamingDetectIntent</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  testcases.  calculateCoverage</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.export</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.import</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.run</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.tools.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  update</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.load</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.consoleSimulatorUser" class="role-title add-link" data-text="Dialogflow Console Simulator User" tabindex="-1">Dialogflow Console Simulator User</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p>Can perform query of dialogflow suggestions in the simulator in web console.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.companionAgents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  companionAgents.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  addPhoneNumber</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  complete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  ack</code></li>
<li><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  participants.  analyzeContent</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  sessions.  detectIntent</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.consoleSmartMessagingAllowlistEditor" class="role-title add-link" data-text="Dialogflow Console Smart Messaging Allowlist Editor" tabindex="-1">Dialogflow Console Smart Messaging Allowlist Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p>Can edit allowlist for smart messaging associated with conversation model in the agent assist console</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationManager" class="role-title add-link" data-text="Dialogflow Conversation Manager" tabindex="-1">Dialogflow Conversation Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Can manage all the resources related to Dialogflow Conversations.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.conversations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  addPhoneNumber</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  complete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.participants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  participants.  analyzeContent</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.entityTypeAdmin" class="role-title add-link" data-text="Dialogflow Entity Type Admin" tabindex="-1">Dialogflow Entity Type Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p>
<p>Can read &amp; write entity types.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.entityTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  createEntity</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  deleteEntity</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.entityTypes.update</code></li>
<li><code dir="ltr" translate="no">dialogflow.  entityTypes.  updateEntity</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.environmentEditor" class="role-title add-link" data-text="Dialogflow Environment editor" tabindex="-1">Dialogflow Environment editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p>Can read &amp; update environment and its sub-resources.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  environments.  getHistory</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  environments.  lookupHistory</code></p>
<p><code dir="ltr" translate="no">dialogflow.  environments.  runContinuousTest</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.update</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.experiments.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.experiments.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.flowEditor" class="role-title add-link" data-text="Dialogflow Flow editor" tabindex="-1">Dialogflow Flow editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p>Can read &amp; update flow and its sub-resources.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.train</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.update</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.validate</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.pages.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.pages.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.versions.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.load</code></li>
<li><code dir="ltr" translate="no">dialogflow.versions.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.integrationManager" class="role-title add-link" data-text="Dialogflow Integration Manager" tabindex="-1">Dialogflow Integration Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.integrationManager</code> )</p>
<p>Can add, remove, enable and disable Dialogflow integrations.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.integrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.integrations.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.integrations.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.intentAdmin" class="role-title add-link" data-text="Dialogflow Intent Admin" tabindex="-1">Dialogflow Intent Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.intentAdmin</code> )</p>
<p>Can read &amp; write intents.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.intents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.intents.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.intents.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.reader" class="role-title add-link" data-text="Dialogflow API Reader" tabindex="-1">Dialogflow API Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p>Grant to Dialogflow API clients that perform Dialogflow-specific read-only calls using the API. Also see <a href="https://docs.cloud.google.com/dialogflow/docs/access-control">Dialogflow access control</a> .</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">dialogflow.agents.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.search</code></p>
<p><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.testCaseAdmin" class="role-title add-link" data-text="Dialogflow Test Case Admin" tabindex="-1">Dialogflow Test Case Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p>
<p>Can read &amp; write test cases.</p></td>
<td><p><code dir="ltr" translate="no">dialogflow.testcases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  testcases.  calculateCoverage</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.export</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.import</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.run</code></li>
<li><code dir="ltr" translate="no">dialogflow.testcases.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.webhookAdmin" class="role-title add-link" data-text="Dialogflow Webhook Admin" tabindex="-1">Dialogflow Webhook Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.webhookAdmin</code> )</p>
<p>Can read &amp; write webhooks.</p>
<blockquote>
<strong>Caution:</strong> Users with permissions to create or modify Dialogflow agent components, such as tools and webhooks, can configure these components to authenticate as the Dialogflow Service Agent using ID tokens. This capability can be used to interact with other Google Cloud services that accept ID token authentication using the permissions granted to the <a href="https://docs.cloud.google.com/iam/docs/service-agents#dialogflow-service-agent">Dialogflow Service Agent</a> . Carefully control who is granted permissions to configure these Dialogflow agent components.
</blockquote></td>
<td><p><code dir="ltr" translate="no">dialogflow.webhooks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.webhooks.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.webhooks.update</code></li>
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
<td><h4 id="dialogflow.serviceAgent" class="role-title add-link" data-text="Dialogflow Service Agent" tabindex="-1">Dialogflow Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</p>
<p>Gives Dialogflow Service Account access to resources on behalf of user project for Integrations (Facebook Messenger, Slack, Telephony, etc.), BigQuery, Discovery Engine, Integration Connectors, Application Integration, and Vertex.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">aiplatform.endpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.predict</code></p>
<p><code dir="ltr" translate="no">aiplatform.extensions.execute</code></p>
<p><code dir="ltr" translate="no">aiplatform.extensions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">ces.apps.get</code></p>
<p><code dir="ltr" translate="no">ces.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ces.sessions.bidiRunSession</code></li>
<li><code dir="ltr" translate="no">ces.sessions.runSession</code></li>
</ul>
<p><code dir="ltr" translate="no">ces.tools.execute</code></p>
<p><code dir="ltr" translate="no">ces.tools.get</code></p>
<p><code dir="ltr" translate="no">ces.toolsets.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></p>
<p><code dir="ltr" translate="no">connectors.actions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.actions.execute</code></li>
<li><code dir="ltr" translate="no">connectors.actions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.  connections.  executeSqlQuery</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  generateOpenAPISpec</code></p>
<p><code dir="ltr" translate="no">connectors.connections.get</code></p>
<p><code dir="ltr" translate="no">connectors.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.entities.create</code></li>
<li><code dir="ltr" translate="no">connectors.entities.delete</code></li>
<li><code dir="ltr" translate="no">connectors.  entities.  deleteEntitiesWithConditions</code></li>
<li><code dir="ltr" translate="no">connectors.entities.get</code></li>
<li><code dir="ltr" translate="no">connectors.entities.list</code></li>
<li><code dir="ltr" translate="no">connectors.entities.update</code></li>
<li><code dir="ltr" translate="no">connectors.  entities.  updateEntitiesWithConditions</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">connectors.operations.get</code></p>
<p><code dir="ltr" translate="no">connectors.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.export</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.search</code></p>
<p><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.changelogs.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.changelogs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.contexts.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.contexts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.conversations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  addPhoneNumber</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  complete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.conversations.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  conversations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.deployments.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.documents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  environments.  runContinuousTest</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.operations.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  participants.  analyzeContent</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.create</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.get</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></li>
<li><code dir="ltr" translate="no">dialogflow.participants.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  create</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  delete</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dialogflow.  sessions.  detectIntent</code></li>
<li><code dir="ltr" translate="no">dialogflow.  sessions.  streamingDetectIntent</code></li>
</ul>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.get</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  collections.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  dataStores.  create</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  dataStores.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  documents.  create</code></p>
<p><code dir="ltr" translate="no">discoveryengine.documents.get</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  documents.  import</code></p>
<p><code dir="ltr" translate="no">discoveryengine.documents.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  documents.  update</code></p>
<p><code dir="ltr" translate="no">discoveryengine.engines.create</code></p>
<p><code dir="ltr" translate="no">discoveryengine.engines.delete</code></p>
<p><code dir="ltr" translate="no">discoveryengine.engines.get</code></p>
<p><code dir="ltr" translate="no">discoveryengine.engines.update</code></p>
<p><code dir="ltr" translate="no">discoveryengine.schemas.get</code></p>
<p><code dir="ltr" translate="no">discoveryengine.schemas.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  servingConfigs.  search</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p>
<p><code dir="ltr" translate="no">integrations.  integrationVersions.  get</code></p>
<p><code dir="ltr" translate="no">integrations.  integrations.  generateOpenApiSpec</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.seek</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.routes.invoke</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">speakerid.phrases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speakerid.phrases.create</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.delete</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.get</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">speakerid.speakers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speakerid.speakers.create</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.delete</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.get</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.list</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.verify</code></li>
</ul>
<p><code dir="ltr" translate="no">speech.adaptations.execute</code></p>
<p><code dir="ltr" translate="no">speech.customClasses.get</code></p>
<p><code dir="ltr" translate="no">speech.customClasses.list</code></p>
<p><code dir="ltr" translate="no">speech.phraseSets.get</code></p>
<p><code dir="ltr" translate="no">speech.phraseSets.list</code></p>
<p><code dir="ltr" translate="no">speech.recognizers.get</code></p>
<p><code dir="ltr" translate="no">speech.recognizers.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
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
<td><h4 id="dialogflow.agents.create" class="permission-name add-link" data-text="dialogflow.agents.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.agents.delete" class="permission-name add-link" data-text="dialogflow.agents.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.agents.export" class="permission-name add-link" data-text="dialogflow.agents.export" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.agents.get" class="permission-name add-link" data-text="dialogflow.agents.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.agents.import" class="permission-name add-link" data-text="dialogflow.agents.import" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.agents.list" class="permission-name add-link" data-text="dialogflow.agents.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.agents.restore" class="permission-name add-link" data-text="dialogflow.agents.restore" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.agents.search" class="permission-name add-link" data-text="dialogflow.agents.search" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.agents.searchResources" class="permission-name add-link" data-text="dialogflow.agents.searchResources" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  agents.  searchResources</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.agents.train" class="permission-name add-link" data-text="dialogflow.agents.train" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.train</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.agents.update" class="permission-name add-link" data-text="dialogflow.agents.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.agents.validate" class="permission-name add-link" data-text="dialogflow.agents.validate" tabindex="-1"><code dir="ltr" translate="no">dialogflow.agents.validate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.answerrecords.delete" class="permission-name add-link" data-text="dialogflow.answerrecords.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  answerrecords.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.answerrecords.get" class="permission-name add-link" data-text="dialogflow.answerrecords.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.answerrecords.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.answerrecords.list" class="permission-name add-link" data-text="dialogflow.answerrecords.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.answerrecords.update" class="permission-name add-link" data-text="dialogflow.answerrecords.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  answerrecords.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.callMatchers.create" class="permission-name add-link" data-text="dialogflow.callMatchers.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.callMatchers.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.callMatchers.delete" class="permission-name add-link" data-text="dialogflow.callMatchers.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.callMatchers.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.callMatchers.list" class="permission-name add-link" data-text="dialogflow.callMatchers.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.changelogs.get" class="permission-name add-link" data-text="dialogflow.changelogs.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.changelogs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.changelogs.list" class="permission-name add-link" data-text="dialogflow.changelogs.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.changelogs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.companionAgents.create" class="permission-name add-link" data-text="dialogflow.companionAgents.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  companionAgents.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.companionAgents.delete" class="permission-name add-link" data-text="dialogflow.companionAgents.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  companionAgents.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.companionAgents.get" class="permission-name add-link" data-text="dialogflow.companionAgents.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.companionAgents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.companionAgents.list" class="permission-name add-link" data-text="dialogflow.companionAgents.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.companionAgents.update" class="permission-name add-link" data-text="dialogflow.companionAgents.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  companionAgents.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.contexts.create" class="permission-name add-link" data-text="dialogflow.contexts.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.contexts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.contexts.delete" class="permission-name add-link" data-text="dialogflow.contexts.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.contexts.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.contexts.get" class="permission-name add-link" data-text="dialogflow.contexts.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.contexts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.contexts.list" class="permission-name add-link" data-text="dialogflow.contexts.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.contexts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.contexts.update" class="permission-name add-link" data-text="dialogflow.contexts.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.contexts.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversationDatasets.create" class="permission-name add-link" data-text="dialogflow.conversationDatasets.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationDatasets.delete" class="permission-name add-link" data-text="dialogflow.conversationDatasets.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversationDatasets.get" class="permission-name add-link" data-text="dialogflow.conversationDatasets.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationDatasets.import" class="permission-name add-link" data-text="dialogflow.conversationDatasets.import" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversationDatasets.list" class="permission-name add-link" data-text="dialogflow.conversationDatasets.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationModels.create" class="permission-name add-link" data-text="dialogflow.conversationModels.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationModels.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversationModels.delete" class="permission-name add-link" data-text="dialogflow.conversationModels.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationModels.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationModels.deploy" class="permission-name add-link" data-text="dialogflow.conversationModels.deploy" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationModels.  deploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversationModels.get" class="permission-name add-link" data-text="dialogflow.conversationModels.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationModels.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationModels.list" class="permission-name add-link" data-text="dialogflow.conversationModels.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversationModels.undeploy" class="permission-name add-link" data-text="dialogflow.conversationModels.undeploy" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationModels.  undeploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationProfiles.create" class="permission-name add-link" data-text="dialogflow.conversationProfiles.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversationProfiles.delete" class="permission-name add-link" data-text="dialogflow.conversationProfiles.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationProfiles.get" class="permission-name add-link" data-text="dialogflow.conversationProfiles.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversationProfiles.list" class="permission-name add-link" data-text="dialogflow.conversationProfiles.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversationProfiles.update" class="permission-name add-link" data-text="dialogflow.conversationProfiles.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversations.addPhoneNumber" class="permission-name add-link" data-text="dialogflow.conversations.addPhoneNumber" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversations.  addPhoneNumber</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversations.complete" class="permission-name add-link" data-text="dialogflow.conversations.complete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversations.  complete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversations.create" class="permission-name add-link" data-text="dialogflow.conversations.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversations.get" class="permission-name add-link" data-text="dialogflow.conversations.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.conversations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.conversations.list" class="permission-name add-link" data-text="dialogflow.conversations.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.conversations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.conversations.update" class="permission-name add-link" data-text="dialogflow.conversations.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  conversations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.deployments.get" class="permission-name add-link" data-text="dialogflow.deployments.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.deployments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.deployments.list" class="permission-name add-link" data-text="dialogflow.deployments.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.deployments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.documents.create" class="permission-name add-link" data-text="dialogflow.documents.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.documents.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.documents.delete" class="permission-name add-link" data-text="dialogflow.documents.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.documents.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.documents.get" class="permission-name add-link" data-text="dialogflow.documents.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.documents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.documents.list" class="permission-name add-link" data-text="dialogflow.documents.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.documents.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.encryptionspec.get" class="permission-name add-link" data-text="dialogflow.encryptionspec.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.encryptionspec.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.encryptionspec.update" class="permission-name add-link" data-text="dialogflow.encryptionspec.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  encryptionspec.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.entityTypes.create" class="permission-name add-link" data-text="dialogflow.entityTypes.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.entityTypes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.entityTypes.createEntity" class="permission-name add-link" data-text="dialogflow.entityTypes.createEntity" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  entityTypes.  createEntity</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.entityTypes.delete" class="permission-name add-link" data-text="dialogflow.entityTypes.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.entityTypes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.entityTypes.deleteEntity" class="permission-name add-link" data-text="dialogflow.entityTypes.deleteEntity" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  entityTypes.  deleteEntity</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.entityTypes.get" class="permission-name add-link" data-text="dialogflow.entityTypes.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.entityTypes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.entityTypes.list" class="permission-name add-link" data-text="dialogflow.entityTypes.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.entityTypes.update" class="permission-name add-link" data-text="dialogflow.entityTypes.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.entityTypes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.entityTypes.updateEntity" class="permission-name add-link" data-text="dialogflow.entityTypes.updateEntity" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  entityTypes.  updateEntity</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.entityTypeAdmin">Dialogflow Entity Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.entityTypeAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.environments.create" class="permission-name add-link" data-text="dialogflow.environments.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.environments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.environments.delete" class="permission-name add-link" data-text="dialogflow.environments.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.environments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.environments.get" class="permission-name add-link" data-text="dialogflow.environments.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.environments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.environments.getHistory" class="permission-name add-link" data-text="dialogflow.environments.getHistory" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  environments.  getHistory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.environments.list" class="permission-name add-link" data-text="dialogflow.environments.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.environments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.environments.lookupHistory" class="permission-name add-link" data-text="dialogflow.environments.lookupHistory" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  environments.  lookupHistory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.environments.runContinuousTest" class="permission-name add-link" data-text="dialogflow.environments.runContinuousTest" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  environments.  runContinuousTest</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.environments.update" class="permission-name add-link" data-text="dialogflow.environments.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.environments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.examples.create" class="permission-name add-link" data-text="dialogflow.examples.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.examples.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.examples.delete" class="permission-name add-link" data-text="dialogflow.examples.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.examples.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.examples.get" class="permission-name add-link" data-text="dialogflow.examples.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.examples.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.examples.list" class="permission-name add-link" data-text="dialogflow.examples.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.examples.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.examples.update" class="permission-name add-link" data-text="dialogflow.examples.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.examples.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.experiments.create" class="permission-name add-link" data-text="dialogflow.experiments.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.experiments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.experiments.delete" class="permission-name add-link" data-text="dialogflow.experiments.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.experiments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.experiments.get" class="permission-name add-link" data-text="dialogflow.experiments.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.experiments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.experiments.list" class="permission-name add-link" data-text="dialogflow.experiments.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.experiments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.experiments.update" class="permission-name add-link" data-text="dialogflow.experiments.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.experiments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.environmentEditor">Dialogflow Environment editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.environmentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.flows.create" class="permission-name add-link" data-text="dialogflow.flows.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.flows.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.flows.delete" class="permission-name add-link" data-text="dialogflow.flows.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.flows.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.flows.get" class="permission-name add-link" data-text="dialogflow.flows.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.flows.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.flows.list" class="permission-name add-link" data-text="dialogflow.flows.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.flows.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.flows.train" class="permission-name add-link" data-text="dialogflow.flows.train" tabindex="-1"><code dir="ltr" translate="no">dialogflow.flows.train</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.flows.update" class="permission-name add-link" data-text="dialogflow.flows.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.flows.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.flows.validate" class="permission-name add-link" data-text="dialogflow.flows.validate" tabindex="-1"><code dir="ltr" translate="no">dialogflow.flows.validate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.fulfillments.get" class="permission-name add-link" data-text="dialogflow.fulfillments.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.fulfillments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.fulfillments.update" class="permission-name add-link" data-text="dialogflow.fulfillments.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.fulfillments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.generators.create" class="permission-name add-link" data-text="dialogflow.generators.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.generators.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.generators.delete" class="permission-name add-link" data-text="dialogflow.generators.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.generators.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.generators.get" class="permission-name add-link" data-text="dialogflow.generators.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.generators.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.generators.list" class="permission-name add-link" data-text="dialogflow.generators.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.generators.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.generators.update" class="permission-name add-link" data-text="dialogflow.generators.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.generators.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.integrations.create" class="permission-name add-link" data-text="dialogflow.integrations.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.integrations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.integrationManager</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.integrations.delete" class="permission-name add-link" data-text="dialogflow.integrations.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.integrations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.integrationManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.integrations.get" class="permission-name add-link" data-text="dialogflow.integrations.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.integrations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.integrationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.integrations.list" class="permission-name add-link" data-text="dialogflow.integrations.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.integrations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.integrationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.integrations.update" class="permission-name add-link" data-text="dialogflow.integrations.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.integrations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.integrationManager">Dialogflow Integration Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.integrationManager</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.intents.create" class="permission-name add-link" data-text="dialogflow.intents.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.intents.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.intentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.intents.delete" class="permission-name add-link" data-text="dialogflow.intents.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.intents.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.intentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.intents.get" class="permission-name add-link" data-text="dialogflow.intents.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.intents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.intentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.intents.list" class="permission-name add-link" data-text="dialogflow.intents.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.intents.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.intentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.intents.update" class="permission-name add-link" data-text="dialogflow.intents.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.intents.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.intentAdmin">Dialogflow Intent Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.intentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.interactionMonitoringAlerts.ack" class="permission-name add-link" data-text="dialogflow.interactionMonitoringAlerts.ack" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  ack</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.interactionMonitoringAlerts.get" class="permission-name add-link" data-text="dialogflow.interactionMonitoringAlerts.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  interactionMonitoringAlerts.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.knowledgeBases.create" class="permission-name add-link" data-text="dialogflow.knowledgeBases.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.knowledgeBases.delete" class="permission-name add-link" data-text="dialogflow.knowledgeBases.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.knowledgeBases.get" class="permission-name add-link" data-text="dialogflow.knowledgeBases.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.knowledgeBases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.knowledgeBases.list" class="permission-name add-link" data-text="dialogflow.knowledgeBases.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.knowledgeBases.update" class="permission-name add-link" data-text="dialogflow.knowledgeBases.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  knowledgeBases.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.messages.list" class="permission-name add-link" data-text="dialogflow.messages.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.messages.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.modelEvaluations.get" class="permission-name add-link" data-text="dialogflow.modelEvaluations.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.modelEvaluations.list" class="permission-name add-link" data-text="dialogflow.modelEvaluations.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.operations.get" class="permission-name add-link" data-text="dialogflow.operations.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.pages.create" class="permission-name add-link" data-text="dialogflow.pages.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.pages.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.pages.delete" class="permission-name add-link" data-text="dialogflow.pages.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.pages.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.pages.get" class="permission-name add-link" data-text="dialogflow.pages.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.pages.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.pages.list" class="permission-name add-link" data-text="dialogflow.pages.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.pages.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.pages.update" class="permission-name add-link" data-text="dialogflow.pages.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.pages.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.participants.analyzeContent" class="permission-name add-link" data-text="dialogflow.participants.analyzeContent" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  participants.  analyzeContent</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.participants.create" class="permission-name add-link" data-text="dialogflow.participants.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.participants.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.participants.get" class="permission-name add-link" data-text="dialogflow.participants.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.participants.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.participants.list" class="permission-name add-link" data-text="dialogflow.participants.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.participants.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.participants.suggest" class="permission-name add-link" data-text="dialogflow.participants.suggest" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  participants.  suggest</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.participants.update" class="permission-name add-link" data-text="dialogflow.participants.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.participants.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.conversationManager">Dialogflow Conversation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.conversationManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.phoneNumberOrders.cancel" class="permission-name add-link" data-text="dialogflow.phoneNumberOrders.cancel" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.phoneNumberOrders.create" class="permission-name add-link" data-text="dialogflow.phoneNumberOrders.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.phoneNumberOrders.get" class="permission-name add-link" data-text="dialogflow.phoneNumberOrders.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.phoneNumberOrders.list" class="permission-name add-link" data-text="dialogflow.phoneNumberOrders.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.phoneNumberOrders.update" class="permission-name add-link" data-text="dialogflow.phoneNumberOrders.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.phoneNumbers.delete" class="permission-name add-link" data-text="dialogflow.phoneNumbers.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.phoneNumbers.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.phoneNumbers.list" class="permission-name add-link" data-text="dialogflow.phoneNumbers.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.phoneNumbers.undelete" class="permission-name add-link" data-text="dialogflow.phoneNumbers.undelete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  phoneNumbers.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.phoneNumbers.update" class="permission-name add-link" data-text="dialogflow.phoneNumbers.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.phoneNumbers.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.playbooks.create" class="permission-name add-link" data-text="dialogflow.playbooks.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.playbooks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.playbooks.delete" class="permission-name add-link" data-text="dialogflow.playbooks.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.playbooks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.playbooks.get" class="permission-name add-link" data-text="dialogflow.playbooks.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.playbooks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.playbooks.list" class="permission-name add-link" data-text="dialogflow.playbooks.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.playbooks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.playbooks.update" class="permission-name add-link" data-text="dialogflow.playbooks.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.playbooks.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.securitySettings.create" class="permission-name add-link" data-text="dialogflow.securitySettings.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  securitySettings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.securitySettings.delete" class="permission-name add-link" data-text="dialogflow.securitySettings.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  securitySettings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.securitySettings.get" class="permission-name add-link" data-text="dialogflow.securitySettings.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  securitySettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.securitySettings.list" class="permission-name add-link" data-text="dialogflow.securitySettings.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.securitySettings.update" class="permission-name add-link" data-text="dialogflow.securitySettings.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  securitySettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.sessionEntityTypes.create" class="permission-name add-link" data-text="dialogflow.sessionEntityTypes.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.sessionEntityTypes.delete" class="permission-name add-link" data-text="dialogflow.sessionEntityTypes.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.sessionEntityTypes.get" class="permission-name add-link" data-text="dialogflow.sessionEntityTypes.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.sessionEntityTypes.list" class="permission-name add-link" data-text="dialogflow.sessionEntityTypes.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.sessionEntityTypes.update" class="permission-name add-link" data-text="dialogflow.sessionEntityTypes.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.sessions.detectIntent" class="permission-name add-link" data-text="dialogflow.sessions.detectIntent" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  sessions.  detectIntent</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.agentAssistClient">Dialogflow Agent Assist Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.agentAssistClient</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.sessions.streamingDetectIntent" class="permission-name add-link" data-text="dialogflow.sessions.streamingDetectIntent" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  sessions.  streamingDetectIntent</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.client">Dialogflow API Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.smartMessagingEntries.create" class="permission-name add-link" data-text="dialogflow.smartMessagingEntries.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.smartMessagingEntries.delete" class="permission-name add-link" data-text="dialogflow.smartMessagingEntries.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.smartMessagingEntries.get" class="permission-name add-link" data-text="dialogflow.smartMessagingEntries.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.smartMessagingEntries.list" class="permission-name add-link" data-text="dialogflow.smartMessagingEntries.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.testcases.calculateCoverage" class="permission-name add-link" data-text="dialogflow.testcases.calculateCoverage" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  testcases.  calculateCoverage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.testcases.create" class="permission-name add-link" data-text="dialogflow.testcases.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.testcases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.testcases.delete" class="permission-name add-link" data-text="dialogflow.testcases.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.testcases.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.testcases.export" class="permission-name add-link" data-text="dialogflow.testcases.export" tabindex="-1"><code dir="ltr" translate="no">dialogflow.testcases.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.testcases.get" class="permission-name add-link" data-text="dialogflow.testcases.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.testcases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.testcases.import" class="permission-name add-link" data-text="dialogflow.testcases.import" tabindex="-1"><code dir="ltr" translate="no">dialogflow.testcases.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.testcases.list" class="permission-name add-link" data-text="dialogflow.testcases.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.testcases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.testcases.run" class="permission-name add-link" data-text="dialogflow.testcases.run" tabindex="-1"><code dir="ltr" translate="no">dialogflow.testcases.run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.testcases.update" class="permission-name add-link" data-text="dialogflow.testcases.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.testcases.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.testCaseAdmin">Dialogflow Test Case Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.testCaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.tools.create" class="permission-name add-link" data-text="dialogflow.tools.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.tools.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.tools.delete" class="permission-name add-link" data-text="dialogflow.tools.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.tools.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.tools.get" class="permission-name add-link" data-text="dialogflow.tools.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.tools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.tools.list" class="permission-name add-link" data-text="dialogflow.tools.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.tools.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.tools.update" class="permission-name add-link" data-text="dialogflow.tools.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.tools.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.transitionRouteGroups.create" class="permission-name add-link" data-text="dialogflow.transitionRouteGroups.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.transitionRouteGroups.delete" class="permission-name add-link" data-text="dialogflow.transitionRouteGroups.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.transitionRouteGroups.get" class="permission-name add-link" data-text="dialogflow.transitionRouteGroups.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.transitionRouteGroups.list" class="permission-name add-link" data-text="dialogflow.transitionRouteGroups.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.transitionRouteGroups.update" class="permission-name add-link" data-text="dialogflow.transitionRouteGroups.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.versions.create" class="permission-name add-link" data-text="dialogflow.versions.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.versions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.versions.delete" class="permission-name add-link" data-text="dialogflow.versions.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.versions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.versions.get" class="permission-name add-link" data-text="dialogflow.versions.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.versions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.versions.list" class="permission-name add-link" data-text="dialogflow.versions.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.versions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.versions.load" class="permission-name add-link" data-text="dialogflow.versions.load" tabindex="-1"><code dir="ltr" translate="no">dialogflow.versions.load</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.versions.update" class="permission-name add-link" data-text="dialogflow.versions.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.versions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.flowEditor">Dialogflow Flow editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.flowEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.webhooks.create" class="permission-name add-link" data-text="dialogflow.webhooks.create" tabindex="-1"><code dir="ltr" translate="no">dialogflow.webhooks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.webhookAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.webhooks.delete" class="permission-name add-link" data-text="dialogflow.webhooks.delete" tabindex="-1"><code dir="ltr" translate="no">dialogflow.webhooks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.webhookAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.webhooks.get" class="permission-name add-link" data-text="dialogflow.webhooks.get" tabindex="-1"><code dir="ltr" translate="no">dialogflow.webhooks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.webhookAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dialogflow.webhooks.list" class="permission-name add-link" data-text="dialogflow.webhooks.list" tabindex="-1"><code dir="ltr" translate="no">dialogflow.webhooks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.webhookAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow.webhooks.update" class="permission-name add-link" data-text="dialogflow.webhooks.update" tabindex="-1"><code dir="ltr" translate="no">dialogflow.webhooks.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.webhookAdmin">Dialogflow Webhook Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.webhookAdmin</code> )</p></td>
</tr>
</tbody>
</table>
