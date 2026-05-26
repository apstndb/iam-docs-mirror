---
name: documents/docs.cloud.google.com/iam/docs/workforce-log-in-gcloud
uri: https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud
title: Sign in to the gcloud CLI with your federated identity
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This document describes how to sign in to the Google Cloud CLI with your federated identity by using a browser-based sign in.

## Before you begin

1.  Ensure that your administrator has set up and configured [Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/workforce-identity-federation) .

2.  Ensure that you have information that supports one of the following options. Your administrator can provide this information.
    
      - **Workforce identity pool and provider IDs** : a workforce identity pool ID and a workforce identity pool provider ID that you can use to [create a login configuration file](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud#use-pool-provider-ids) .
    
      - **Existing configuration file** : a path to an existing login configuration file that you can use to [sign in to the gcloud CLI](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud#sign-in-gcloud) .
    
      - **Configuration file contents** : configuration file contents that you can [save to a configuration file](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud#save-configuration-file) .

## Obtain a login configuration file

This section describes how you can obtain a login configuration file that you can use to sign in to the gcloud CLI.

### Create a login configuration file

You can use the workforce identity pool ID and workforce identity pool provider ID to create a login configuration file.

To create the login configuration file, run the following command. You can optionally activate the file as the default for the gcloud CLI by adding the [`--activate` flag](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/create-login-config) . You can then run `gcloud auth login` without specifying the configuration file path each time.

    gcloud iam workforce-pools create-login-config \
        locations/global/workforcePools/WORKFORCE_POOL_ID/providers/PROVIDER_ID \
        --output-file=LOGIN_CONFIG_FILE_PATH

Replace the following:

  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID
  - `  PROVIDER_ID  ` : the provider ID
  - `  LOGIN_CONFIG_FILE_PATH  ` : the path to a configuration file that you specify—for example, `login.json`

The file contains the endpoints used by the gcloud CLI to enable the browser-based authentication flow and set the audience to the IdP that was configured in the workforce identity pool provider. The file doesn't contain confidential information.

The output looks similar to the following:

    {
      "type": "external_account_authorized_user_login_config",
      "audience": "//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID",
      "auth_url": "https://auth.cloud.google/authorize",
      "token_url": "https://sts.googleapis.com/v1/oauthtoken",
      "token_info_url": "https://sts.googleapis.com/v1/introspect"
    }

> **Caution:** We recommend that you first ensure that the contents of this file are correct and then safeguard the file—for example, by making it read-only and restricting access with an ACL. The file isn't validated; a malicious actor with write access to this file can change the endpoints and intercept credentials.

To stop `gcloud auth login` from using this configuration file automatically, you can unset it by running `gcloud config unset auth/login_config_file` .

You can now [sign in to the gcloud CLI](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud#sign-in-gcloud) .

### Save a login configuration file

You can save credential configuration file contents that were provided to you to a file. Note the path, and then [sign in to the gcloud CLI](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud#sign-in-gcloud) .

## Sign in to the gcloud CLI

To sign in to the gcloud CLI with a login configuration file, run the following command:

    gcloud auth login --login-config="LOGIN_CONFIG_FILE_PATH"

Replace `  LOGIN_CONFIG_FILE_PATH  ` with the path to the login configuration file, if you haven't activated this file before. However, if you have previously activated this file using the `--activate` flag, then you don't need to specify the file again. Instead, run the following command:

    gcloud auth login
