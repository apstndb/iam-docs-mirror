---
name: documents/docs.cloud.google.com/iam/docs/create-and-deploy-agent
uri: https://docs.cloud.google.com/iam/docs/create-and-deploy-agent
title: Create and deploy an agent with Agent CLI and Agent Identity
description: Create and deploy an agent with Agent CLI and Agent Identity.
data_source: docs.cloud.google.com
---

> **Preview**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

This guide shows you how to create and deploy an agent in Agent Runtime on Gemini Enterprise Agent Platform with Agent Identity enabled.

Agent Identity assigns a secure SPIFFE identity to your deployed agent. The agent uses this identity to authenticate to Google Cloud services and retrieve credentials from the Agent Identity auth manager.

## Before you begin

1.  Enable the Agent Identity Connector API.
    
    **Roles required to enable APIs**
    
    To enable APIs, you need the Service Usage Admin IAM role ( `roles/serviceusage.serviceUsageAdmin` ), which contains the `serviceusage.services.enable` permission. [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

2.  Ensure you have the **Vertex AI User** ( `roles/aiplatform.user` ) role on your project.

## Create and deploy the agent

Create a sample agent using `agents-cli` and deploy it with Agent Identity:

1.  Install `google-agents-cli` and `uv` , then run the setup:
    
        pip install google-agents-cli uv
        agents-cli setup

2.  Create a new agent project using the prototype template:
    
        agents-cli create AGENT_PROJECT --prototype --yes
    
    Replace `  AGENT_PROJECT  ` with the name for your new agent project directory (for example, `maps-agent` ).
    
    This command generates the following project directory structure:
    
    *(Note: The following tree highlights the relevant configuration files and might not represent all files in your directory.)*
    
        AGENT_PROJECT/
        ├── app/                       # Core agent code
        │   ├── agent.py               # Main agent logic
        │   ├── fast_api_app.py        # Client application logic
        │   └── app_utils/             # App utilities and helpers
        ├── tests/                     # Unit and integration tests
        ├── GEMINI.md                  # Development guide
        └── pyproject.toml                # Project dependencies

3.  Rename the default application folder ( `app` ) to match your agent name ( `  AGENT_NAME  ` , for example, `maps_agent` ):
    
        mv app AGENT_NAME
    
    Then, update your `agent.py` configuration file to reflect the new name:
    
        # In AGENT_PROJECT/AGENT_NAME/agent.pyapp=App(root_agent=root_agent,name="AGENT_NAME",)

4.  Enable Agent Identity by creating a config file:
    
        echo '{ "identity_type": "AGENT_IDENTITY" }' > .agent_engine_config.json

5.  Create a `requirements.txt` file for the deployment dependencies:
    
        echo "httpx" > requirements.txt
        echo "google-auth" >> requirements.txt
        echo "google-adk[agent_engines,agent-identity]" >> requirements.txt
        echo "google-cloud-aiplatform[agent_engines,adk]>=1.153.1" >> requirements.txt

6.  Verify the project directory structure:
    
        AGENT_PROJECT/
        ├── AGENT_NAME/                   # Agent application folder
        │   ├── .agent_engine_config.json # Agent Identity configuration
        │   ├── agent.py                  # Main agent logic
        │   ├── fast_api_app.py           # Client application logic
        │   ├── requirements.txt          # Deployment dependencies
        │   └── app_utils/                # App helpers
        ├── tests/                        # Tests
        ├── GEMINI.md                     # Development guide
        └── pyproject.toml                # Project dependencies
    
    Verify your agent locally:
    
        uv run adk web . --port 8501 --reload_agents
    
    To validate your agent, do the following:
    
    1.  Go to `http://localhost:8501` .
    2.  In the chat interface, send a test prompt to verify the response.

7.  Deploy your agent to Google Cloud:
    
        uv run adk deploy agent_engine AGENT_NAME \    --project="PROJECT_ID" \    --region="LOCATION"
    
    Replace the following:
    
      - `  PROJECT_ID  ` : Your Google Cloud project ID.
      - `  LOCATION  ` : The region where you want to deploy the agent (for example, `us-west1` ).
    
    When deployment completes, the CLI outputs a confirmation message and a link to your agent's playground in the Google Cloud console.

8.  Retrieve your agent's SPIFFE ID (Agent Identity) from the Google Cloud console:
    
    1.  In the Google Cloud console, go to the **Agent Platform** page.
    2.  Click the **Deployments** tab and select your deployed agent.
    3.  Copy the **Agent Identity** value (for example, `principal://agents.global.org-ORGANIZATION_ID.system.id.goog/resources/aiplatform/projects/PROJECT_NUMBER/locations/LOCATION/reasoningEngines/ENGINE_ID` ).

## What's next

  - [Agent Identity overview](https://docs.cloud.google.com/iam/docs/agent-identity-overview)
  - [Agent Identity auth manager overview](https://docs.cloud.google.com/iam/docs/auth-manager-overview)
  - [Authenticate using 3-legged OAuth with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-3lo)
  - [Authenticate using 2-legged OAuth with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-2lo)
  - [Authenticate using API key with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-api-key)
