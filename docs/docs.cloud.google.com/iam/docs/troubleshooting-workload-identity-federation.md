---
name: documents/docs.cloud.google.com/iam/docs/troubleshooting-workload-identity-federation
uri: https://docs.cloud.google.com/iam/docs/troubleshooting-workload-identity-federation
title: Troubleshoot Workload Identity Federation
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page describes resolutions for common [Workload Identity Federation](https://docs.cloud.google.com/iam/docs/workload-identity-federation) errors.

## Google Cloud API does not accept the credential issued from `SecurityTokenService`

Access tokens returned by the [`SecurityTokenService`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/TopLevel/token) API are [federated access tokens](https://docs.cloud.google.com/docs/authentication/token-types#fed-access-tokens) . Although most Google Cloud APIs support identity federation, certain API methods might have limitations. For a list of limitations, see [Identity federation: products and limitations](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services) .

If you encounter the following error, you might be attempting to use a federated access token with a service that doesn't support them.

    {
      "error": {
        "code": 401,
        "message": "Request had invalid authentication credentials. Expected OAuth 2 access token, login cookie or other valid authentication credential. See https://developers.google.com/identity/sign-in/web/devconsole-project.",
        "status": "UNAUTHENTICATED",
      }
    }

To resolve this error, exchange the federated access token for an unrestricted access token by calling [`GenerateAccessToken`](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateAccessToken) . For more information, see [Obtaining short-lived credentials with identity federation](https://docs.cloud.google.com/iam/docs/using-workload-identity-federation) .

## Allowlist an identity provider for use with Workload Identity Federation

If you attempt to configure a disallowed identity provider as a workload identity pool provider, you encounter the following error:

    FAILED_PRECONDITION: Precondition check failed.
    - '@type': type.googleapis.com/google.rpc.PreconditionFailure
      violations:
      - description: "Org Policy violated for value: '{PROVIDER}'."
        subject: orgpolicy:projects/{PROJECT}/locations/global/workloadIdentityPools/{POOL}
        type: constraints/iam.workloadIdentityPoolProviders

To resolve this issue, follow the directions on [Restrict identity provider configuration](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#restrict) to allowlist the identity provider for use with Workload Identity Federation.

## Input JWK is not in a valid json format

If you are configuring an OIDC provider and you receive the error `Input JWK is not in a valid json format` , it can be because endpoints that are secured with self-signed certificates aren't supported by Google Cloud. Specifically, the `x5c` and `x5t` fields aren't supported and must be removed from the OIDC JWK.

To resolve issues with your JWK, do the following:

1.  Edit your JWK and remove the `x5c` (X.509 Certificate Chain) and `x5t` (X.509 Certificate SHA-1 Thumbprint) fields.
    
        {
          "kty": "RSA",
          "use": "sig",
          "kid": "example-key-id",
          "alg": "RS256",
          "n": "base64url-modulus",
          "e": "AQAB"
        }

2.  Verify that the remaining JWK fields are properly formatted as described in the [OIDC specification](https://openid.net/specs/openid-connect-core-1_0.html#JWKS) .

3.  Configure the OIDC provider with the updated JWK.

## Error connecting to the given credential's issuer

If you receive the following error, it might be because Google Cloud is unable to fetch your IdP's OIDC metadata document or JWKS:

    {
      "error": "invalid_grant",
      "error_description":"Error connecting to the given credential's issuer."
     }

This error usually occurs because the endpoints aren't configured to be reachable from the public internet. To resolve this error, check that the OIDC endpoint is publicly available and compliant with the OIDC specification. For more information, see [Preparing the external identity provider](https://docs.cloud.google.com/iam/docs/configuring-workload-identity-federation#oidc) .

If you still receive the error, check that the token issuer, the `iss` claim in the token correct.

## Mapped google.subject claim exceeds the 127 bytes limit

If you receive the following error, it's because the incoming credentials received by the [`SecurityTokenService`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/TopLevel/token) API generate a `google.subject` claim that exceeds the character limit:

    {
      "error": "invalid_request",
      "error_description":"The size of mapped attribute google.subject exceeds the 127 bytes limit. Either modify your attribute mapping or the incoming assertion to produce a mapped attribute that is less than 127 bytes."
     }

To resolve this issue, use the [`extract` function](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#extract) to remove unnecessary characters and extract a unique subject identifier from a longer claim, for example:

    google.subject=assertion.sub.extract('/users/{sub_claim}')

## Error 429 Too Many Requests

If you receive the error `429 Too Many Requests` , while requesting a token from the [`SecurityTokenService`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/TopLevel/token) API, it means that your Google Cloud project has exceeded its rate quota limit for the API.

The error includes a message similar to the following:

    {
      "error": "quota_exceeded",
      "error_description":"The request was throttled due to rate limit: sts.googleapis.com/requests. Please retry after a few seconds."
     }

To resolve this issue, identify the `sts.googleapis.com/requests` metric name provided in the error message, locate the corresponding metric name in the [IAM Quota page](https://console.cloud.google.com/iam-admin/quotas) , confirm that the usage percentage exceeds the quota, and then request a quota increase.
