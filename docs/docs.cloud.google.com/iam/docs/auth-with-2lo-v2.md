---
name: documents/docs.cloud.google.com/iam/docs/auth-with-2lo-v2
uri: https://docs.cloud.google.com/iam/docs/auth-with-2lo-v2
title: Authenticate using 2-legged OAuth with auth manager
description: Configure 2-legged OAuth auth providers in Agent Identity auth manager to let agents authenticate to external tools like ServiceNow or Salesforce using their own authority.
data_source: docs.cloud.google.com
---

To let your agents authenticate to external tools like ServiceNow or Salesforce using their own authority, configure outbound authentication using 2-legged OAuth (Client Credentials) auth providers in Agent Identity auth manager.

By managing credentials and tokens, 2-legged OAuth auth providers remove the need for custom code to handle authentication flows.

> **Important:** This document shows how to authenticate by using the Agent Identity API. We recommend using the Agent Identity API because the [IAM Connectors API](https://docs.cloud.google.com/iam/docs/auth-with-2lo) ( [Preview](https://docs.cloud.google.com/products#product-launch-stages) ) will not be [generally available](https://docs.cloud.google.com/products#product-launch-stages) . If you are using the IAM Connectors API, then [migrate to the Agent Identity API](https://docs.cloud.google.com/iam/docs/migrate-to-agent-identity-api) .

## 2-legged OAuth workflow

2-legged OAuth auth providers use the agent's identity and don't require user consent. Google manages the storage of the client credentials. When you use the Agent Development Kit (ADK), it automatically retrieves and injects the resulting access tokens into the tool invocation headers.

## Before you begin

1.  [Verify that you have chosen the correct authentication method](https://docs.cloud.google.com/iam/docs/agent-identity-overview#auth-models) .

2.  Enable the Agent Identity API.
    
    **Roles required to enable APIs**
    
    To enable APIs, you need the `serviceusage.services.enable` permission. If you created the project, then you likely already have this permission through the Owner role ( `roles/owner` ). Otherwise, you can get this permission through the Service Usage Admin role ( `roles/serviceusage.serviceUsageAdmin` ). [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

3.  [Create and deploy an agent](https://docs.cloud.google.com/iam/docs/create-and-deploy-agent) .

4.  Obtain the **client ID** and **client secret** from the third-party application that you want to connect to.

5.  [Verify that you have the roles required to complete this task](https://docs.cloud.google.com/iam/docs/auth-with-2lo-v2#req-roles) .

### Required roles

To get the permissions that you need to create and use a 2-legged Agent Identity auth provider, ask your administrator to grant you the following IAM roles on the project:

  - To create auth providers:
      - [Agent Identity Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin) ( `roles/agentidentity.admin` )
      - [Agent Identity Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor) ( `roles/agentidentity.editor` )
  - To use auth providers:
      - [Agent Identity User](https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.user) ( `roles/agentidentity.user` )
      - [Agent Default Access](https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentDefaultAccess) ( `roles/aiplatform.agentDefaultAccess` )
      - [Agent Context Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentContextEditor) ( `roles/aiplatform.agentContextEditor` )
      - [Vertex AI User](https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.user) ( `roles/aiplatform.user` )
      - [Service Usage Consumer](https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer) ( `roles/serviceusage.serviceUsageConsumer` )

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to create and use a 2-legged Agent Identity auth provider. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to create and use a 2-legged Agent Identity auth provider:

  - To create auth providers: `agentidentity.authProviders.create`
  - To use auth providers:
      - `agentidentity.authProviders.retrieveCredentials`
      - `aiplatform.endpoints.predict`
      - `aiplatform.sessions.create`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Create a 2-legged auth provider

Create an auth provider to define the configuration and credentials for third-party applications.

To create a 2-legged auth provider, use the Google Cloud console or the Google Cloud CLI.

### Console

1.  In the Google Cloud console, go to the **Agent Registry** page.

2.  Click the name of the agent that you want to create an auth provider for.

3.  Click **Identity** .

4.  In the **Auth Providers** section, click **add Add auth provider** .

5.  In the **Add auth provider** pane, enter a name and description.
    
    The name can contain only lowercase letters, numbers, or hyphens, cannot end with a hyphen, and must start with a lowercase letter.

6.  From the **OAuth Type** list, select **OAuth (2 legged)** .

7.  Click **Create and continue** .

8.  To grant your agent identity permission to use the auth provider, click **Grant access** .
    
    This process automatically assigns the **Agent Identity User** ( `roles/agentidentity.user` ) role to the agent identity on the auth provider resource.

9.  In the **Auth provider credentials** section, enter the following information:
    
      - **Client ID**
      - **Client Secret**
      - **Token URL**

10. Click **Add provider config** .

The newly created auth provider appears in the **Auth Providers** list.

### gcloud CLI

1.  Create the auth provider:
    
        gcloud agent-identity auth-providers create AUTH_PROVIDER_NAME \    --location="LOCATION" \    --two-legged-oauth-client-id="CLIENT_ID" \    --two-legged-oauth-client-secret="CLIENT_SECRET" \    --two-legged-oauth-token-url="TOKEN_URL"

2.  Verify that your auth provider appears in the list and its state is `ENABLED` :
    
        gcloud agent-identity auth-providers list \   --project="PROJECT_ID" \   --location="LOCATION"

3.  Grant access permissions to allow your agent and local development environment to retrieve credentials from the auth provider. To allow your deployed agent and your personal user account to access the auth provider, grant the **Agent Identity User** ( `roles/agentidentity.user` ) role on the auth provider resource:
    
    1.  Grant access to your deployed agent's SPIFFE ID (Agent Identity):
        
            gcloud agent-identity auth-providers add-iam-policy-binding AUTH_PROVIDER_NAME \    --project="PROJECT_ID" \    --location="LOCATION" \    --role="roles/agentidentity.user" \    --member="principal://agents.global.org-ORGANIZATION_ID.system.id.goog/resources/aiplatform/projects/PROJECT_NUMBER/locations/LOCATION/reasoningEngines/ENGINE_ID"
    
    2.  Grant access to your personal user account for local development and testing ( `adk web` ):
        
            gcloud agent-identity auth-providers add-iam-policy-binding AUTH_PROVIDER_NAME \    --project="PROJECT_ID" \    --location="LOCATION" \    --role="roles/agentidentity.user" \    --member="user:USER_EMAIL"

Replace the following:

  - `  PROJECT_ID  ` : Your Google Cloud project ID.
  - `  LOCATION  ` : The location where your auth provider and agent are deployed (for example, `us-west1` ).
  - `  AUTH_PROVIDER_NAME  ` : The name for your auth provider (for example, `jira-mcp-2lo-authprovider` ).
  - `  CLIENT_ID  ` : The OAuth client ID you generated from the third-party service.
  - `  CLIENT_SECRET  ` : The OAuth client secret you generated from the third-party service.
  - `  TOKEN_URL  ` : The token server URL (for example, `https://oauth2.googleapis.com/token` ).
  - `  ORGANIZATION_ID  ` : Your Google Cloud organization ID.
  - `  PROJECT_NUMBER  ` : Your Google Cloud project number.
  - `  ENGINE_ID  ` : The ID of your deployed reasoning engine agent.
  - `  USER_EMAIL  ` : Your personal user account email address.

## Authenticate in your agent code

To authenticate your agent, you can use the ADK.

### ADK

Reference the auth provider in your agent's code by using the MCP toolset in the ADK.

    from google.adk.agents importAgentfrom google.adk.auth.credential_manager importCredentialManagerfrom google.adk.integrations.agent_identity importGcpAuthProvider,GcpAuthProviderSchemefrom google.adk.tools.mcp_tool.mcp_session_manager importStreamableHTTPConnectionParamsfrom google.adk.tools.mcp_tool.mcp_toolset importMcpToolsetfrom google.adk.auth.auth_tool importAuthConfig# Register the Google Cloud Auth Provider so the CredentialManager can use it.CredentialManager.register_auth_provider(GcpAuthProvider())# Create the Google Cloud Auth Provider scheme# Note: If using the legacy V1 API, the resource name uses 'connectors'# instead of 'authProviders': projects/.../connectors/...auth_scheme=GcpAuthProviderScheme(name="projects/PROJECT_ID/locations/LOCATION/authProviders/AUTH_PROVIDER_NAME")# Configure an MCP tool with the authentication scheme.toolset=McpToolset(connection_params=StreamableHTTPConnectionParams(url="https://YOUR_MCP_SERVER_URL"),auth_scheme=auth_scheme,)# Initialize the agent with the authenticated tools.agent=Agent(name="AGENT_NAME",model="gemini-2.5-flash",instruction="AGENT_INSTRUCTIONS",tools=[toolset],)

### ADK

Reference the auth provider in your agent's code using an authenticated function tool in the ADK.

    import httpxfrom google.adk.agents importAgentfrom google.adk.auth.credential_manager importCredentialManagerfrom google.adk.integrations.agent_identity importGcpAuthProviderfrom google.adk.integrations.agent_identity importGcpAuthProviderSchemefrom google.adk.apps importAppfrom google.adk.auth.auth_credential importAuthCredentialfrom google.adk.auth.auth_tool importAuthConfigfrom google.adk.tools.authenticated_function_tool importAuthenticatedFunctionToolfrom vertexai importagent_engines# First, register Google Cloud auth providerCredentialManager.register_auth_provider(GcpAuthProvider())# Create Auth Config# Note: If using the legacy V1 API, the resource name uses 'connectors'# instead of 'authProviders': projects/.../connectors/...spotify_auth_config=AuthConfig(auth_scheme=GcpAuthProviderScheme(name=("projects/PROJECT_ID/locations/""LOCATION/authProviders/""AUTH_PROVIDER_NAME")))# Use the Auth Config in Authenticated Function Toolspotify_search_track_tool=AuthenticatedFunctionTool(func=spotify_search_track,auth_config=spotify_auth_config)# Sample function toolasyncdef spotify_search_track(credential:AuthCredential,query:str)->str|list:token=Noneifcredential.httpandcredential.http.credentials:token=credential.http.credentials.tokenifnottoken:return"Error: No authentication token available."asyncwithhttpx.AsyncClient()asclient:response=awaitclient.get("https://api.spotify.com/v1/search",headers={"Authorization":f"Bearer {token}"},params={"q":query,"type":"track","limit":1},)# Add your own logic hereagent=Agent(name="AGENT_NAME",model="MODEL_NAME",instruction="AGENT_INSTRUCTIONS",tools=[spotify_search_track_tool],)app=App(name="APP_NAME",root_agent=agent,)vertex_app=agent_engines.AdkApp(app_name=app)

### ADK

Reference the auth provider in your agent's code using the Agent Registry MCP toolset in the ADK.

    from google.adk.agents importAgentfrom google.adk.auth.credential_manager importCredentialManagerfrom google.adk.integrations.agent_identity importGcpAuthProviderfrom google.adk.integrations.agent_identity importGcpAuthProviderSchemefrom google.adk.tools.mcp_tool.mcp_session_manager importStreamableHTTPConnectionParamsfrom google.adk.tools.mcp_tool.mcp_toolset importMcpToolsetfrom google.adk.auth.auth_tool importAuthConfigfrom google.adk.integrations.agent_registry importAgentRegistry# First, register Google Cloud auth providerCredentialManager.register_auth_provider(GcpAuthProvider())# Create Google Cloud auth provider scheme# Note: If using the legacy V1 API, the resource name uses 'connectors'# instead of 'authProviders': projects/.../connectors/...auth_scheme=GcpAuthProviderScheme(name=("projects/PROJECT_ID/locations/""LOCATION/authProviders/""AUTH_PROVIDER_NAME"))# Set Agent Registryregistry=AgentRegistry(project_id="PROJECT_ID",location="global")toolset=registry.get_mcp_toolset(mcp_server_name=("projects/PROJECT_ID/locations/""global/mcpServers/""agentregistry-00000000-0000-0000-0000-000000000000"),auth_scheme=auth_scheme,)# Example MCP tooltoolset=McpToolset(connection_params=StreamableHTTPConnectionParams(url="MCP_URL"),auth_scheme=auth_scheme,)agent=Agent(name="AGENT_NAME",model="MODEL_NAME",instruction="AGENT_INSTRUCTIONS",tools=[toolset],)

## Install dependencies for local testing

To test your agent locally in a virtual environment, install the following necessary dependencies:

1.  Create and activate a virtual environment:
    
        python3 -m venv env
        source env/bin/activate

2.  Install the required packages:
    
        pip install google-cloud-aiplatform[agent_engines,adk] google-adk[agent-identity]

## Deploy the agent

When you deploy your agent to Google Cloud, make sure that Agent Identity is enabled.

### Agent CLI

If you're using the Agent Development Kit (ADK) and the Agent CLI, do the following to deploy your agent with Agent Identity enabled:

1.  In your agent application folder, create a configuration file named `.agent_engine_config.json` to enable Agent Identity:
    
        echo '{ "identity_type": "AGENT_IDENTITY" }' > AGENT_NAME/.agent_engine_config.json

2.  Deploy your agent to Agent Runtime on Gemini Enterprise Agent Platform :
    
        uv run adk deploy agent_engine AGENT_NAME \    --project="PROJECT_ID" \    --region="LOCATION"
    
    Replace the following:
    
      - `  AGENT_NAME  ` : The name of your agent application folder (for example, `maps_agent` ).
      - `  PROJECT_ID  ` : Your Google Cloud project ID.
      - `  LOCATION  ` : The supported region where you want to deploy the agent (for example, `us-west1` ).

### Python SDK

If you're deploying programmatically using the Vertex AI Python SDK, use the `identity_type=AGENT_IDENTITY` flag:

    import vertexaifrom vertexai importtypesfrom vertexai.agent_engines importAdkApp# Initialize the Vertex AI client with v1beta1 API for Agent Identity supportclient=vertexai.Client(project="PROJECT_ID",location="LOCATION",http_options=dict(api_version="v1beta1"))# Use the proper wrapper class for your Agent Framework (e.g., AdkApp)app=AdkApp(agent=agent)# Deploy the agent with Agent Identity enabledremote_app=client.agent_engines.create(agent=app,config={"identity_type":types.IdentityType.AGENT_IDENTITY,"requirements":["google-cloud-aiplatform[agent_engines,adk]","google-adk[agent-identity,mcp]>=2.7.1",],},)

Replace the following:

  - `  PROJECT_ID  ` : Your Google Cloud project ID.
  - `  LOCATION  ` : The supported region where you want to deploy the agent (for example, `us-west1` ).

## What's next

  - [Agent Identity overview](https://docs.cloud.google.com/iam/docs/agent-identity-overview)
  - [Authenticate using 3-legged OAuth with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2)
  - [Authenticate using API key with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-api-key-v2)
  - [Manage Agent Identity auth providers](https://docs.cloud.google.com/iam/docs/manage-auth-providers-v2)
  - [Troubleshoot Agent Identity auth manager](https://docs.cloud.google.com/iam/docs/troubleshoot-auth-manager)
