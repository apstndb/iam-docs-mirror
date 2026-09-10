---
name: documents/docs.cloud.google.com/iam/docs/full-resource-names
uri: https://docs.cloud.google.com/iam/docs/full-resource-names
title: Full resource names
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

Some Identity and Access Management (IAM) features, such as [troubleshooting access issues](https://docs.cloud.google.com/iam/docs/troubleshoot-policies) and [viewing the grantable roles on a resource](https://docs.cloud.google.com/iam/docs/viewing-grantable-roles) , require you to provide a *full resource name* .

> **Note:** IAM Conditions also accepts resource names for a limited number of services. For details, see the [resource attribute reference](https://docs.cloud.google.com/iam/docs/conditions-resource-attributes#resource-name) for IAM Conditions.

This page provides examples of full resource names for commonly used Google Cloud services. It is not a complete list. To learn more about how full resource names are formatted, see the [resource names](https://docs.cloud.google.com/apis/design/resource_names) section of the API design guide.

| Resource type                                                                                                                       | Full resource name format                                                                                                                               |
| ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BigQuery [datasets](https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/datasets)                                         | ` //bigquery.googleapis.com/projects/         PROJECT_ID        /datasets/         DATASET_ID        `                                                  |
| Cloud Billing [accounts](https://docs.cloud.google.com/billing/docs/reference/rest/v1/billingAccounts)                              | ` //cloudbilling.googleapis.com/billingAccounts/         BILLING_ACCOUNT_ID        `                                                                    |
| Cloud Run [services](https://docs.cloud.google.com/run/docs/reference/rest/v2/projects.locations.services)                          | ` //run.googleapis.com/projects/         PROJECT_ID        /locations/         LOCATION_ID        /services/         SERVICE_ID        `                |
| Spanner [instances](https://docs.cloud.google.com/spanner/docs/reference/rest/v1/projects.instances)                                | ` //spanner.googleapis.com/projects/         PROJECT_ID        /instances/         INSTANCE_ID        `                                                 |
| Cloud SQL [instances](https://docs.cloud.google.com/sql/docs/mysql/admin-api/rest/v1beta4/instances)                                | ` //cloudsql.googleapis.com/projects/         PROJECT_ID        /instances/         INSTANCE_ID        `                                                |
| Cloud Storage [buckets](https://docs.cloud.google.com/storage/docs/json_api/v1/buckets) <sup>1</sup>                                | ` //storage.googleapis.com/projects/_/buckets/         BUCKET_ID        `                                                                               |
| Compute Engine [instances](https://docs.cloud.google.com/compute/docs/reference/rest/v1/instances)                                  | ` //compute.googleapis.com/projects/         PROJECT_ID        /zones/         ZONE        /instances/         INSTANCE_ID        `                     |
| Compute Engine [networks](https://docs.cloud.google.com/compute/docs/reference/rest/v1/networks)                                    | ` //compute.googleapis.com/projects/         PROJECT_ID        /global/networks/         NETWORK        `                                               |
| Compute Engine [subnetworks](https://docs.cloud.google.com/compute/docs/reference/rest/v1/subnetworks)                              | ` //compute.googleapis.com/projects/         PROJECT_ID        /regions/         REGION        /subnetworks/         SUBNETWORK        `                |
| Google Kubernetes Engine [clusters](https://docs.cloud.google.com/kubernetes-engine/docs/reference/rest/v1/projects.zones.clusters) | ` //container.googleapis.com/projects/         PROJECT_ID        /clusters/         CLUSTER_ID        `                                                 |
| IAM [service accounts](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts)                           | ` //iam.googleapis.com/projects/         PROJECT_ID        /  serviceAccounts/         SERVICE_ACCOUNT_EMAIL        `                                   |
| IAM [service account keys](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys)                  | ` //iam.googleapis.com/projects/         PROJECT_ID        /  serviceAccounts/         SERVICE_ACCOUNT_EMAIL        /keys/         KEY_ID        `      |
| Identity-Aware Proxy [App Engine app service](https://docs.cloud.google.com/iap/docs/reference/compute-engine-apis)                 | ` //iap.googleapis.com/projects/         PROJECT_NUMBER        /iap_web/appengine-         PROJECT_ID        /services/         APP_SERVICE_ID        ` |
| Identity-Aware Proxy [Compute Engine backend service](https://docs.cloud.google.com/iap/docs/reference/app-engine-apis)             | ` //iap.googleapis.com/projects/         PROJECT_NUMBER        /iap_web/compute/services/         BACKEND_SERVICE_ID_OR_NAME        `                   |
| Pub/Sub [topics](https://docs.cloud.google.com/pubsub/docs/reference/rest/v1/projects.topics)                                       | ` //pubsub.googleapis.com/projects/         PROJECT_ID        /topics/         TOPIC_ID        `                                                        |
| Resource Manager [organizations](https://docs.cloud.google.com/resource-manager/reference/rest/v3/organizations)                    | ` //cloudresourcemanager.googleapis.com/organizations/         ORGANIZATION_NUMBER        `                                                             |
| Resource Manager [folders](https://docs.cloud.google.com/resource-manager/reference/rest/v3/folders)                                | ` //cloudresourcemanager.googleapis.com/folders/         FOLDER_NUMBER        `                                                                         |
| Resource Manager [projects](https://docs.cloud.google.com/resource-manager/reference/rest/v3/projects)                              | ` //cloudresourcemanager.googleapis.com/projects/         PROJECT_ID        `                                                                           |

<sup>1</sup> The format shown here is compatible with IAM. Some services use a different format for this resource type.

## What's next

  - Learn how to [troubleshoot access issues](https://docs.cloud.google.com/iam/docs/troubleshoot-policies) for a resource.
  - Understand how to [view the roles you can grant](https://docs.cloud.google.com/iam/docs/viewing-grantable-roles) on a resource.
