---
name: Azure CDN
x-slug: azure-cdn
description: Ensuring a consistent user experience is important. If your websites
  or mobile apps involve streaming media, gaming software, firmware updates (Smart
  TVs, consumer electronic appliances) or IoT endpoints (cars, sensors), Content Delivery
  Network helps you reduce load times, save bandwidth, and increase responsiveness.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Endpoints
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/apis.md
specificationVersion: "0.14"
apis:
- name: CdnManagementClient - Endpoints List By Profile
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get
  description: Lists existing CDN endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-openapi.md
- name: CdnManagementClient - Endpoints Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get
  description: Gets an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-openapi.md
- name: CdnManagementClient - Endpoints Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put
  description: Creates a new CDN endpoint with the specified endpoint name under the
    specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put-openapi.md
- name: CdnManagementClient - Endpoints Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch
  description: Updates an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile. Only tags and Origin HostHeader
    can be updated after creating an endpoint. To update origins, use the Update Origin
    operation. To update custom domains, use the Update Custom Domain operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch-openapi.md
- name: CdnManagementClient - Endpoints Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete
  description: Deletes an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-openapi.md
- name: CdnManagementClient - Endpoints Start
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post
  description: Starts an existing CDN endpoint that is on a stopped state.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-openapi.md
- name: CdnManagementClient - Endpoints Stop
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post
  description: Stops an existing running CDN endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-openapi.md
- name: CdnManagementClient - Endpoints Purge Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post
  description: Removes a content from CDN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post-openapi.md
- name: CdnManagementClient - Endpoints Load Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post
  description: Pre-loads a content to CDN. Available for Verizon Profiles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post-openapi.md
- name: CdnManagementClient - Endpoints List Resource Usage
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post
  description: Checks the quota and usage of geo filters and custom domains under
    the given endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-openapi.md
- name: CdnManagementClient - Origins List By Endpoint
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get
  description: Lists all of the existing origins within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-openapi.md
- name: CdnManagementClient - Endpoints List By Profile
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get
  description: Lists existing CDN endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-openapi.md
- name: CdnManagementClient - Endpoints Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get
  description: Gets an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-openapi.md
- name: CdnManagementClient - Endpoints Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put
  description: Creates a new CDN endpoint with the specified endpoint name under the
    specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put-openapi.md
- name: CdnManagementClient - Endpoints Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch
  description: Updates an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile. Only tags and Origin HostHeader
    can be updated after creating an endpoint. To update origins, use the Update Origin
    operation. To update custom domains, use the Update Custom Domain operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch-openapi.md
- name: CdnManagementClient - Endpoints Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete
  description: Deletes an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-openapi.md
- name: CdnManagementClient - Endpoints Start
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post
  description: Starts an existing CDN endpoint that is on a stopped state.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-openapi.md
- name: CdnManagementClient - Endpoints Stop
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post
  description: Stops an existing running CDN endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-openapi.md
- name: CdnManagementClient - Endpoints Purge Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post
  description: Removes a content from CDN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post-openapi.md
- name: CdnManagementClient - Endpoints Load Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post
  description: Pre-loads a content to CDN. Available for Verizon Profiles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post-openapi.md
- name: CdnManagementClient - Endpoints List Resource Usage
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post
  description: Checks the quota and usage of geo filters and custom domains under
    the given endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-openapi.md
- name: CdnManagementClient - Origins List By Endpoint
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get
  description: Lists all of the existing origins within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-openapi.md
- name: CdnManagementClient - Origins List By Endpoint
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get
  description: Lists all of the existing origins within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-openapi.md
- name: CdnManagementClient - Endpoints List Resource Usage
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post
  description: Checks the quota and usage of geo filters and custom domains under
    the given endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-openapi.md
- name: CdnManagementClient - Endpoints Load Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post
  description: Pre-loads a content to CDN. Available for Verizon Profiles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post-openapi.md
- name: CdnManagementClient - Endpoints Purge Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post
  description: Removes a content from CDN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post-openapi.md
- name: CdnManagementClient - Endpoints Stop
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post
  description: Stops an existing running CDN endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-openapi.md
- name: CdnManagementClient - Endpoints Start
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post
  description: Starts an existing CDN endpoint that is on a stopped state.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-openapi.md
- name: CdnManagementClient - Endpoints Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete
  description: Deletes an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-openapi.md
- name: CdnManagementClient - Endpoints Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch
  description: Updates an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile. Only tags and Origin HostHeader
    can be updated after creating an endpoint. To update origins, use the Update Origin
    operation. To update custom domains, use the Update Custom Domain operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch-openapi.md
- name: CdnManagementClient - Endpoints Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put
  description: Creates a new CDN endpoint with the specified endpoint name under the
    specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put-openapi.md
- name: CdnManagementClient - Endpoints Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get
  description: Gets an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-openapi.md
- name: CdnManagementClient - Endpoints List By Profile
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get
  description: Lists existing CDN endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.blockchain.workbench.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.cdn.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/cdn/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cdn/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cdn/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---