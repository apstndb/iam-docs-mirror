---
name: documents/docs.cloud.google.com/iam/docs/workforce-console-sso
uri: https://docs.cloud.google.com/iam/docs/workforce-console-sso
title: Set up user access to the console (federated)
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This guide shows you how to set up access to the Google Cloud Workforce Identity Federation console, also known as the console (federated), from your identity provider (IdP) and shows you how to provide access instructions to your users.

## Before you begin

1.  [Configure Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/configuring-workforce-identity-federation) in your Google Cloud organization, including a [workforce identity pool](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#workforce-identity-pools) and a [workforce identity pool provider](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#workforce-identity-pool-providers) . Alternatively, if you use one of the following IdPs, see the IdP-specific guides for more information:
    
      - [Configure Microsoft Entra ID-based Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/workforce-sign-in-microsoft-entra-id)
      - [Configure Okta-based Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/workforce-sign-in-okta)

2.  Note your workforce identity pool provider name, which you use later in this guide.

> **Note:** For personalization features, such as the user's display name and photo to be displayed correctly, you must configure [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) .

## Set up redirect URLs in your IdP

You can configure your IdP to post an IdP response and redirect your user to the console (federated) after your user authenticates. To do this, you must configure a redirect URL and set it in your IdP configuration.

To create the redirect URL, do the following:

1.  Share the name of the workforce identity pool provider with your users. It is formatted as follows:
    
        locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID
    
    Replace the following:
    
      - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID.
      - `  WORKFORCE_PROVIDER_ID  ` : the workforce identity provider ID.

2.  Create the redirect URL. It is formatted as follows:
    
        https://auth.cloud.google/signin-callback/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID

3.  Configure your IdP with the redirect URL.
    
    In your IdP, enter the redirect URL. The field into which you enter the URL can vary.
    
    ### OIDC
    
    In your IdP, the field might be called `Redirect URL` or `Callback URL` .
    
    Your IdP sends the response and name token to this URL.
    
    ### SAML
    
    In your IdP, the field might be called `Single sign-on URL` or `SAML assertion consumer service (ACS) URL` .
    
    Your IdP posts the SAML assertion to this URL.
    
    If you want to enable IdP-initiated login with your SAML provider, enter the following URL in the `Default RelayState` setting, or its equivalent. The IdP redirects your user to this URL after your user successfully authenticates:
    
        https://console.cloud.google/

## Inform your users how to sign in

This section describes the different ways your users can sign in to the console (federated).

### Start the sign-in process using an SSO link

To start the sign-in process with your IdP, you can share a link with your users that redirects them to your IdP without prompting them for the provider name. After users successfully login, they are automatically redirected to the console (federated).

To use this method, send the following login link to your users:

    https://auth.cloud.google/signin/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID?continueUrl=https://console.cloud.google/

### Start the sign-in process using the console (federated)

To start the sign-in process at the console (federated), do the following:

1.  Provide your users with your workforce identity pool provider name described earlier in this document.

2.  Provide your users with the following link to the console (federated):
    
        https://console.cloud.google/

When your users first access the console (federated), they are prompted to enter the workforce identity pool provider name. They are then redirected to your IdP to authenticate. After they authenticate, they are redirected back to the console (federated).

### Use SAML IdP-initiated sign-in

The SAML specification defines a flow called [IdP-initiated sign-in](https://auth0.com/docs/authenticate/protocols/saml/saml-sso-integrations/configure-idp-initiated-saml-sign-on-to-oidc-apps) , in which users initiate the sign-in process at the IdP. If your IdP supports this flow, you can share the details with your users.

## Use the console (federated) vs. the Google Cloud console

The [console (federated)](https://console.cloud.google/) provides limited access to only those Google Cloud products that support Workforce Identity Federation. Because of this, when using the console (federated), you see a limited number of Google Cloud products, and the product UIs themselves might have further limitations when viewed in the console (federated).

To learn more about products that support Workforce Identity Federation and related limitations, see [Identity federation: supported products and limitations](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services) .

The Google Cloud console, by comparison, can provide full access to all products and features, depending on roles granted to users.

## What's next

  - [Identity federation: supported products and limitations](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services)
