---
name: documents/docs.cloud.google.com/iam/docs/workforce-oauth-app
uri: https://docs.cloud.google.com/iam/docs/workforce-oauth-app
title: OAuth application integration overview
description: Overview of OAuth application integration.
data_source: docs.cloud.google.com
---

This page provides an overview of OAuth application integration in Google Cloud.

You can use OAuth application integration to integrate your OAuth-based applications with Google Cloud. Federated users can use their identity provider (IdP) to sign in to the applications and access their Google Cloud products and data. OAuth application integration is a feature of Workforce Identity Federation.

To use OAuth application integration, you must first create a workforce identity pool and provider. You can then register the OAuth-based application using OAuth 2.0. Applications must be registered in the organization where your workforce identity pool and provider are configured.

> **Important:** OAuth application integration works only with Identity-Aware Proxy.

## OAuth application registration

To configure an application to access Google Cloud, you [register](https://docs.cloud.google.com/iam/docs/workforce-manage-oauth-app#create) the application with Google Cloud by creating [OAuth client credentials](https://tools.ietf.org/html/rfc6749#section-4.4) . The credential contains a client secret. The application uses the access token to access the Google Cloud products and data.

## OAuth client and credential security risks and mitigations

You must secure access to the IAM APIs and the client ID and secret. If the client ID and secret is leaked, security issues can result. These issues include the following:

  - Impersonation: A malicious user with your client ID and secret can create an application that masquerades as your legitimate application. They can then do the following:
    
      - Gain unauthorized access to the user data and permissions that your application is entitled to.
      - Perform actions on the user's behalf, such as posting content, making API calls, or modifying user settings.
      - Perform phishing attacks, wherein the malicious user creates a fake login page that resembles the OAuth provider. The page can then trick users into entering their credentials, which gives the credentials to the malicious user who can then access their accounts.

  - Reputational damage: A security breach can harm the reputation of your application and organization, causing users to lose trust.

In the event of a breach, to mitigate these and other risks, assess the nature of the breach and do the following:

  - Ensure that only trusted users have IAM access to the [OAuth client and credential API](https://docs.cloud.google.com/iam/docs/workforce-manage-oauth-app) .

  - Rotate the client secret immediately, by rotating the client credential, as follows:
    
    1.  [Create a new client credential](https://docs.cloud.google.com/iam/docs/workforce-manage-oauth-app#create-credential) for the OAuth client.
    2.  [Disable the old client credential](https://docs.cloud.google.com/iam/docs/workforce-manage-oauth-app#disable-credential) .
    3.  [Delete the old client credential](https://docs.cloud.google.com/iam/docs/workforce-manage-oauth-app#delete-credential) .

# What's next

  - Learn how to [Manage OAuth applications](https://docs.cloud.google.com/iam/docs/workforce-manage-oauth-app) .
