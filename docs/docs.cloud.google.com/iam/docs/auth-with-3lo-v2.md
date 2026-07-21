---
name: documents/docs.cloud.google.com/iam/docs/auth-with-3lo-v2
uri: https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2
title: Authenticate using 3-legged OAuth with auth manager
description: Configure 3-legged OAuth auth providers in Agent Identity auth manager to let agents authenticate to external tools like Jira or GitHub on behalf of users.
data_source: docs.cloud.google.com
---

> **Preview**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

To grant your agent access to external tools and services (such as Jira tasks or GitHub repositories) on behalf of a specific end user, configure a 3-legged OAuth auth provider in the Agent Identity auth manager.

By managing credentials and tokens, 3-legged OAuth auth providers remove the need for custom code to handle authentication flows.

> **Important:** This document shows how to authenticate by using the Agent Identity API. We recommend using the Agent Identity API because the [IAM Connectors API](https://docs.cloud.google.com/iam/docs/auth-with-3lo) [(preview)](https://docs.cloud.google.com/products#product-launch-stages) will not be [generally available](https://docs.cloud.google.com/products#product-launch-stages) . If you are using the IAM Connectors API, then [migrate to the Agent Identity API](https://docs.cloud.google.com/iam/docs/migrate-to-agent-identity-api) .

## 3-legged OAuth workflow

3-legged OAuth auth providers require user consent because the agent accesses resources on behalf of the user.

1.  **Prompt and redirection** : The chat interface prompts the user to sign in and then redirects the user to the third-party application's consent page.
2.  **Consent and storage** : After the user grants permission, the Agent Identity auth manager stores the resulting OAuth tokens in a Google-managed credential vault.
3.  **Injection** : When you use the Agent Development Kit (ADK), the agent automatically retrieves the token from the auth provider and injects it into the tool invocation headers.

## Before you begin

1.  [Verify that you have chosen the correct authentication method](https://docs.cloud.google.com/iam/docs/agent-identity-overview#auth-models) .

2.  Enable the Agent Identity API.
    
    **Roles required to enable APIs**
    
    To enable APIs, you need the `serviceusage.services.enable` permission. If you created the project, then you likely already have this permission through the Owner role ( `roles/owner` ). Otherwise, you can get this permission through the Service Usage Admin role ( `roles/serviceusage.serviceUsageAdmin` ). [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

3.  [Create and deploy an agent](https://docs.cloud.google.com/iam/docs/create-and-deploy-agent) .

4.  Ensure that you have a frontend application to handle user sign-in prompts and redirection to third-party consent pages.

5.  [Verify that you have the roles required to complete this task](https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2#req-roles) .

### Required roles

To get the permissions that you need to create and use a 3-legged auth provider, ask your administrator to grant you the following IAM roles on the project:

  - To create auth providers:
      - [Agent Identity Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin) ( `roles/agentidentity.admin` )
      - [Agent Identity Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor) ( `roles/agentidentity.editor` )
  - To use auth providers:
      - [Agent Identity User](https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.user) ( `roles/agentidentity.user` )
      - [Vertex AI User](https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.user) ( `roles/aiplatform.user` )
      - [Service Usage Consumer](https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer) ( `roles/serviceusage.serviceUsageConsumer` )

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to create and use a 3-legged auth provider. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to create and use a 3-legged auth provider:

  - To create auth providers: `agentidentity.authProviders.create`
  - To use auth providers:
      - `agentidentity.authProviders.retrieveCredentials`
      - `aiplatform.endpoints.predict`
      - `aiplatform.sessions.create`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Create a 3-legged auth provider

Create an auth provider to define the configuration and credentials for third-party applications.

To create a 3-legged auth provider, use the gcloud CLI:

1.  [Configure your OAuth client application](https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2#configure-oauth-app) to register your client and obtain a client ID and client secret. Specify the redirect URI using the template in that section.

2.  Create the auth provider using your client credentials:
    
        gcloud alpha agent-identity authProviders create AUTH_PROVIDER_NAME \    --project="PROJECT_ID" \    --location="LOCATION" \    --three-legged-oauth-client-id="CLIENT_ID" \    --three-legged-oauth-client-secret="CLIENT_SECRET" \    --three-legged-oauth-authorization-url="AUTHORIZATION_URL" \    --three-legged-oauth-token-url="TOKEN_URL"

3.  Verify that your auth provider appears in the list and its state is `ENABLED` :
    
        gcloud alpha agent-identity authProviders list \   --project="PROJECT_ID" \   --location="LOCATION"

4.  Grant access permissions to allow your agent and local development environment to retrieve credentials from the auth provider. To allow your deployed agent and your personal user account to access the auth provider, grant the **Agent Identity User** ( `roles/agentidentity.user` ) role on the auth provider resource:
    
    1.  Grant access to your deployed agent's SPIFFE ID (Agent Identity):
        
            gcloud alpha agent-identity authProviders add-iam-policy-binding AUTH_PROVIDER_NAME \    --project="PROJECT_ID" \    --location="LOCATION" \    --role="roles/agentidentity.user" \    --member="principal://agents.global.org-ORGANIZATION_ID.system.id.goog/resources/aiplatform/projects/PROJECT_NUMBER/locations/LOCATION/reasoningEngines/ENGINE_ID"
    
    2.  Grant access to your personal user account for local development and testing ( `adk web` ):
        
            gcloud alpha agent-identity authProviders add-iam-policy-binding AUTH_PROVIDER_NAME \    --project="PROJECT_ID" \    --location="LOCATION" \    --role="roles/agentidentity.user" \    --member="user:USER_EMAIL"

Replace the following:

  - `  PROJECT_ID  ` : Your Google Cloud project ID.
  - `  LOCATION  ` : The location where your auth provider and agent are deployed (for example, `us-west1` ).
  - `  AUTH_PROVIDER_NAME  ` : The name for your auth provider (for example, `bigquery-mcp-3lo-authprovider` ).
  - `  AUTHORIZATION_URL  ` : The authorization server URL (for example, `https://accounts.google.com/o/oauth2/v2/auth` ).
  - `  TOKEN_URL  ` : The token server URL (for example, `https://oauth2.googleapis.com/token` ).
  - `  CLIENT_ID  ` : The OAuth client ID you generated from the third-party service.
  - `  CLIENT_SECRET  ` : The OAuth client secret you generated from the third-party service.
  - `  ORGANIZATION_ID  ` : Your Google Cloud organization ID.
  - `  PROJECT_NUMBER  ` : Your Google Cloud project number.
  - `  ENGINE_ID  ` : The ID of your deployed reasoning engine agent.
  - `  USER_EMAIL  ` : Your personal user account email address.

## Configure your OAuth client application

Before you register your OAuth client credentials, obtain a client ID and client secret from the third-party authorization server (for example, Google, GitHub, or Jira).

If you're connecting to a third-party service outside of Google Cloud, obtain the OAuth client credentials from that service's developer portal and skip the steps in this section.

### Register the redirect URI

When you configure your OAuth client credentials, you must register the auth provider's dedicated callback redirect URI.

1.  Construct the redirect URI using the following template:
    
    ` https://agentidentitycredentials.googleapis.com/v1alpha/projects/ PROJECT_ID  ` /locations/ `  LOCATION  ` /authProviders/ `  AUTH_PROVIDER_NAME  ` /oauthcallback
    
    Replace the following:
    
      - `PROJECT_ID` : Your Google Cloud project ID.
      - `LOCATION` : The region where your auth provider will be deployed (for example, `us-west1` ).
      - `AUTH_PROVIDER_NAME` : The name of your auth provider.
    
    For example: `https://agentidentitycredentials.googleapis.com/v1alpha/projects/my-project/locations/us-west1/authProviders/bigquery-mcp-3lo-authprovider/oauthcallback`

2.  If you're connecting to Google Cloud services (such as BigQuery), you can configure the consent screen and create OAuth client credentials in the Google Cloud console:
    
    1.  Configure the OAuth consent screen:
        
        1.  In the Google Cloud console, go to the **APIs & Services \> OAuth consent screen** page.
        2.  In the **App information** section, enter an application name (such as BigQuery Manager Application) and a support email.
        3.  In the **Audience** section, select **Internal** or **External** .
        4.  Enter your contact information to receive notifications.
        5.  Read and accept the **Google API Services User Data Policy** .
        6.  Click **Finish** .
    
    2.  Create your OAuth client credentials:
        
        1.  In the Google Cloud console, go to the **APIs & Services \> OAuth consent screen \> Clients** page.
        2.  Click **Create credentials \> OAuth client ID** .
        3.  Select the **Web application** option from the list.
        4.  Enter a recognizable name for your OAuth client.
        5.  In the **Authorized redirect URIs** section, click **Add URI** and enter your constructed redirect URI.
        6.  Click **Create** . In the **OAuth client created** dialog, copy your generated **Client ID** and **Client Secret** values.

## Authenticate in your agent code

To authenticate your agent, you can use the ADK or call the Agent Identity API directly.

### ADK

Reference the auth provider in your agent's code using the MCP toolset in the ADK.

    from google.adk.agents.llm_agent importLlmAgentfrom google.adk.auth.credential_manager importCredentialManagerfrom google.adk.integrations.agent_identity importGcpAuthProvider,GcpAuthProviderSchemefrom google.adk.tools.mcp_tool.mcp_session_manager importStreamableHTTPConnectionParamsfrom google.adk.tools.mcp_tool.mcp_toolset importMcpToolsetfrom google.adk.auth.auth_tool importAuthConfig# Register Google Cloud auth providerCredentialManager.register_auth_provider(GcpAuthProvider())# The URI to redirect the user to after consent is granted.CONTINUE_URI="https://YOUR_FRONTEND_URL/validateUserId"# Create auth provider scheme# Note: If using the legacy V1 API, the resource name uses 'connectors'# instead of 'authProviders': projects/.../connectors/...auth_scheme=GcpAuthProviderScheme(name="projects/PROJECT_ID/locations/LOCATION/authProviders/AUTH_PROVIDER_NAME",continue_uri=CONTINUE_URI)# Configure an MCP tool with the authentication scheme.toolset=McpToolset(connection_params=StreamableHTTPConnectionParams(url="https://YOUR_MCP_SERVER_URL"),auth_scheme=auth_scheme,)# Initialize the agent with the authenticated tools.agent=LlmAgent(name="AGENT_NAME",model="gemini-2.5-flash",instruction="AGENT_INSTRUCTIONS",tools=[toolset],)

#### Example: Connecting to BigQuery MCP

The following example shows an `agent.py` configuration that connects an agent to the BigQuery MCP server:

    import osfrom google.adk.agents importAgentfrom google.adk.apps importAppfrom google.adk.auth.credential_manager importCredentialManagerfrom google.adk.integrations.agent_identity importGcpAuthProvider,GcpAuthProviderSchemefrom google.adk.models importGeminifrom google.adk.tools.mcp_tool.mcp_session_manager importStreamableHTTPConnectionParamsfrom google.adk.tools.mcp_tool.mcp_toolset importMcpToolsetimport google.authfrom google.genai importtypes_,project_id=google.auth.default()os.environ["GOOGLE_CLOUD_PROJECT"]="PROJECT_ID"os.environ["GOOGLE_GENAI_USE_VERTEXAI"]="True"bigquery_mcp_auth_provider_id="AUTH_PROVIDER_NAME"bigquery_mcp_endpoint=os.environ.get("BIGQUERY_MCP_ENDPOINT","https://bigquery.googleapis.com/mcp")# Register Google Cloud auth providerCredentialManager.register_auth_provider(GcpAuthProvider())# URI to redirect user to after consent is granted.CONTINUE_URI="http://127.0.0.1:8501/validateUserId"bigquery_mcp_auth_scheme=GcpAuthProviderScheme(name=f"projects/{project_id}/locations/LOCATION/authProviders/{bigquery_mcp_auth_provider_id}",scopes=["https://www.googleapis.com/auth/bigquery"],continue_uri=CONTINUE_URI,)bigquery_mcp_tools=McpToolset(connection_params=StreamableHTTPConnectionParams(url=bigquery_mcp_endpoint),auth_scheme=bigquery_mcp_auth_scheme,errlog=None,)root_agent=Agent(name="root_agent",model=Gemini(model="gemini-2.5-flash",retry_options=types.HttpRetryOptions(attempts=3),),instruction=("You are a helpful AI assistant designed to provide accurate and useful"" information. You can also use your BigQuery MCP tools to look up"" BigQuery data."),tools=[bigquery_mcp_tools],)app=App(root_agent=root_agent,name="AGENT_NAME",)

### ADK

Reference the auth provider in your agent's code using an authenticated function tool in the ADK.

    import httpxfrom google.adk.agents.llm_agent importLlmAgentfrom google.adk.auth.credential_manager importCredentialManagerfrom google.adk.integrations.agent_identity importGcpAuthProviderfrom google.adk.integrations.agent_identity importGcpAuthProviderSchemefrom google.adk.apps importAppfrom google.adk.auth.auth_credential importAuthCredentialfrom google.adk.auth.auth_tool importAuthConfigfrom google.adk.tools.authenticated_function_tool importAuthenticatedFunctionToolfrom vertexai importagent_engines# First, register Google Cloud auth providerCredentialManager.register_auth_provider(GcpAuthProvider())# The URI to redirect the user to after consent is completed.CONTINUE_URI="WEB_APP_VALIDATE_USER_URI"# Create Auth Configspotify_auth_config=AuthConfig(auth_scheme=GcpAuthProviderScheme(name="projects/PROJECT_ID/locations/LOCATION/authProviders/AUTH_PROVIDER_NAME",continue_uri=CONTINUE_URI))# Use the Auth Config in Authenticated Function Toolspotify_search_track_tool=AuthenticatedFunctionTool(func=spotify_search_track,auth_config=spotify_auth_config)# Sample function toolasyncdef spotify_search_track(credential:AuthCredential,query:str)->str|list:token=Noneifcredential.httpandcredential.http.credentials:token=credential.http.credentials.tokenifnottoken:return"Error: No authentication token available."asyncwithhttpx.AsyncClient()asclient:response=awaitclient.get("https://api.spotify.com/v1/search",headers={"Authorization":f"Bearer {token}"},params={"q":query,"type":"track","limit":1},)# Add your own logic hereagent=LlmAgent(name="AGENT_NAME",model="gemini-2.5-flash",instruction="AGENT_INSTRUCTIONS",tools=[spotify_search_track_tool],)app=App(name="APP_NAME",root_agent=agent,)vertex_app=agent_engines.AdkApp(app_name=app)

### ADK

Reference the auth provider in your agent's code using the Agent Registry MCP toolset in the ADK.

    from google.adk.agents.llm_agent importLlmAgentfrom google.adk.auth.credential_manager importCredentialManagerfrom google.adk.integrations.agent_identity importGcpAuthProviderfrom google.adk.integrations.agent_identity importGcpAuthProviderSchemefrom google.adk.tools.mcp_tool.mcp_session_manager importStreamableHTTPConnectionParamsfrom google.adk.tools.mcp_tool.mcp_toolset importMcpToolsetfrom google.adk.auth.auth_tool importAuthConfigfrom google.adk.integrations.agent_registry importAgentRegistry# First, register Google Cloud auth providerCredentialManager.register_auth_provider(GcpAuthProvider())# The URI to redirect the user to after consent is completed.CONTINUE_URI="WEB_APP_VALIDATE_USER_URI"# Create Google Cloud auth provider schemeauth_scheme=GcpAuthProviderScheme(name="projects/PROJECT_ID/locations/LOCATION/authProviders/AUTH_PROVIDER_NAME",continue_uri=CONTINUE_URI)# Set Agent Registryregistry=AgentRegistry(project_id="PROJECT_ID",location="global")toolset=registry.get_mcp_toolset(mcp_server_name=("projects/PROJECT_ID/locations/""global/mcpServers/""agentregistry-00000000-0000-0000-0000-000000000000"),auth_scheme=auth_scheme,)# Example MCP tooltoolset=McpToolset(connection_params=StreamableHTTPConnectionParams(url="MCP_URL"),auth_scheme=auth_scheme,)agent=LlmAgent(name="AGENT_NAME",model="MODEL_NAME",instruction="AGENT_INSTRUCTIONS",tools=[toolset],)

### Call the API directly

If you aren't using the ADK, your agent must call the `agentidentitycredentials.retrieveCredentials` API to get the token.

Because this is a multi-step OAuth flow, your agent must handle the lifecycle of the operation:

1.  **Initial request** : The agent calls `retrieveCredentials` .
2.  **Consent required** : If the user hasn't granted consent, the API returns a response containing the result as `uri_consent_required` . This will contain `authorization_uri` and a `consent_nonce` .
3.  **Frontend redirection** : Your application must redirect the user to the `authorization_uri` .
4.  **Completion** : After the user grants consent, call `FinalizeCredentials` using the `consent_nonce` to complete the flow and obtain the token.

## Update your client-side application

> **Note:** The client UI works with only remote agents.

To handle user sign-in and redirection for 3-legged OAuth, your client-side application must implement the following steps to manage user consent and resume the conversation:

### Sample UI server

You can download and run a complete sample UI server that uses `uvicorn` . Before you begin, ensure that you have a GitHub account and `pip` installed.

To set up and run the sample UI server, do the following:

1.  Clone the `adk-python` GitHub repository:
    
        git clone https://github.com/google/adk-python.git

2.  Navigate to the repository and activate a Python virtual environment:
    
        cd adk-python
        python3 -m venv .venv
        source .venv/bin/activate

3.  Navigate to the sample UI client directory:
    
        cd contributing/samples/integrations/gcp_auth/client

4.  Install the client dependencies:
    
        pip install -r requirements.txt

5.  Before starting the server, set the `AGENT_PROJECT_DIR` environment variable to specify the directory where your agent code is located. Otherwise, the application defaults to looking for agents in the parent folder of the client directory.
    
    Launch the sample UI server using `uvicorn` . Ensure that the port matches the redirect URI configured in your OAuth client:
    
        export AGENT_PROJECT_DIR="/path/to/your/agent_project"
        uvicorn main:app --port 8501 --reload

6.  Open `http://localhost:8501` in your browser. (Note: You must use `localhost` and not `127.0.0.1` , because the OAuth redirect URL specifically requires the `localhost` hostname.) Specify your settings, click **Save & Apply Settings** , and then interact with your agent.

### Custom UI application

To implement these capabilities directly in a custom UI application, perform the following steps:

  - [Handle the authorization trigger](https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2#auth-trigger)
  - [Implement a user validation endpoint](https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2#validation-endpoint)
  - [Resume the agent conversation](https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2#resume-conversation)

#### Handle the authorization trigger

When an agent needs user consent, it returns an `adk_request_credential` function call. Your application must intercept this call to initiate a user authorization dialog or redirect.

Manage the session context by recording the `consent_nonce` provided by the auth provider. This nonce is required to verify the user during the validation step. Save the `auth_config` and `auth_request_function_call_id` values within the session to facilitate resuming the flow after the user grants consent.

    if (fc := get_auth_request_function_call(event_data)):
        print("--> Authentication required by agent.")
        try:
            auth_config = get_auth_config(fc)
            auth_uri, consent_nonce = handle_adk_request_credential(
                auth_config, AUTH_PROVIDER_NAME, request.user_id
            )
            if auth_uri:
                event_data['popup_auth_uri'] = auth_uri
                fc_id = (
                    fc.get('id') if isinstance(fc, dict)
                    else getattr(fc, 'id', None)
                )
                event_data['auth_request_function_call_id'] = fc_id
                event_data['auth_config'] = auth_config.model_dump()
    
                # Store session state
                if session_id:
                    consent_sessions[session_id] = {
                        "user_id": request.user_id,
                        "consent_nonce": consent_nonce
                    }
        except Exception as e:
            print(f"Error handling adk_request_credential: {e}")
            # Optionally, add logic to inform the user about the error.
    
    def handle_adk_request_credential(auth_config, auth_provider_name, user_id):
        ec = auth_config.exchanged_auth_credential
        if ec and ec.oauth2:
            oauth2 = ec.oauth2
            return oauth2.auth_uri, oauth2.nonce
        return None, None

#### Implement a user validation endpoint

Implement a validation endpoint on your web server (the same URI provided as `continue_uri` during configuration). This endpoint must do the following:

1.  Receive `user_id_validation_state` , `auth_provider_name` , and `uuid` as query parameters.
2.  Retrieve the `user_id` and `consent_nonce` values from your session storage. If multiple authorization flows run concurrently, use the `uuid` to match the correct session.
3.  Call the auth provider's `FinalizeCredentials` API with these parameters.
4.  Close the authorization window upon receiving a success response.

##### Example: FastAPI validation endpoint ( `main.py` )

The following example shows a complete FastAPI validation endpoint that handles the OAuth callback and finalizes user credentials:

    @app.api_route("/validateUserId", methods=["GET"])
    async def validate_user(request: Request):
        auth_provider_name = request.query_params.get("auth_provider_name")
        session_id = request.cookies.get("session_id")
        session = consent_sessions.get(session_id, {})
    
        payload = {
            "userId": session.get("user_id"),
            "userIdValidationState": request.query_params.get(
                "user_id_validation_state"
            ),
            "consentNonce": session.get("consent_nonce"),
        }
    
        base_url = "https://agentidentitycredentials.googleapis.com/v1alpha"
        finalize_url = f"{base_url}/{auth_provider_name}/credentials:finalize"
    
        try:
            async with httpx.AsyncClient(timeout=30.0) as client:
                resp = await client.post(finalize_url, json=payload)
                resp.raise_for_status()
        except httpx.HTTPError as e:
            err_text = e.response.text if hasattr(e, "response") else str(e)
            status = e.response.status_code if hasattr(e, "response") else 500
            return HTMLResponse(err_text, status_code=status)
    
        return HTMLResponse("""
            <script>
                window.close();
            </script>
            <p>Success. You can close this window.</p>
        """)

#### Resume the agent conversation

After the user grants consent and the authorization window closes, retrieve the `auth_config` and `auth_request_function_call_id` values from your session data. To continue the conversation, include these details in a new request to the agent as a `function_response` .

    if (request.is_auth_resume and session.auth_request_function_call_id
        and session.auth_config):
        auth_content = types.Content(
            role='user',
            parts=[
                types.Part(
                    function_response=types.FunctionResponse(
                        id=session.auth_request_function_call_id,
                        name='adk_request_credential',
                        response=session.auth_config
                    )
                )
            ],
        )
        # Send message to agent
        async for event in agent.async_stream_query(
            user_id=request.user_id,
            message=auth_content,
            session_id=session_id,
        ):
            # ...

## Deploy the agent

When you deploy your agent to Google Cloud, ensure that Agent Identity is enabled.

If you're deploying to Agent Runtime on Gemini Enterprise Agent Platform , use the `identity_type=AGENT_IDENTITY` flag:

    import vertexai
    from vertexai import types
    from vertexai.agent_engines import AdkApp
    
    # Initialize the Vertex AI client with v1beta1 API for Agent Identity support
    client = vertexai.Client(
        project="PROJECT_ID",
        location="LOCATION",
        http_options=dict(api_version="v1beta1")
    )
    
    # Use the proper wrapper class for your Agent Framework (e.g., AdkApp)
    app = AdkApp(agent=agent)
    
    # Deploy the agent with Agent Identity enabled
    remote_app = client.agent_engines.create(
        agent=app,
        config={
            "identity_type": types.IdentityType.AGENT_IDENTITY,
            "requirements": [
                "google-cloud-aiplatform[agent_engines,adk]",
                "google-adk[agent-identity]"
            ],
        },
    )

## What's next

  - [Troubleshoot Agent Identity authentication issues](https://docs.cloud.google.com/iam/docs/troubleshoot-auth-manager)
  - [Agent Identity overview](https://docs.cloud.google.com/iam/docs/agent-identity-overview)
  - [Authenticate using 2-legged OAuth with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-2lo-v2)
  - [Authenticate using API key with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-api-key-v2)
  - [Manage Agent Identity auth providers](https://docs.cloud.google.com/iam/docs/manage-auth-providers-v2)
