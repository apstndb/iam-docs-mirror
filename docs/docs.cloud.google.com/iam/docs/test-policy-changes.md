---
name: documents/docs.cloud.google.com/iam/docs/test-policy-changes
uri: https://docs.cloud.google.com/iam/docs/test-policy-changes
title: Test changes to allow policies
description: Overview of the tools you can use to test changes to allow policies.
data_source: docs.cloud.google.com
---

Changing an Identity and Access Management (IAM) allow policy can be disruptive, especially if you're revoking access for an active user or service account. Because of this risk, you might want to test allow policy changes before making them to confirm that they won't disrupt anyone's work.

You can use Policy Simulator to see how a change to an allow policy might impact a principal's access before you commit to making the change. Testing these changes helps ensure that the changes you're making won't cause a principal to lose access that they need.

To learn more about Policy Simulator, see the [Policy Simulator overview](https://docs.cloud.google.com/policy-intelligence/docs/iam-simulator-overview) in the Policy Intelligence documentation.
