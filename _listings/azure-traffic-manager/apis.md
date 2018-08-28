---
name: Azure Traffic Manager
x-slug: azure-traffic-manager
description: 'Azure Traffic Manager gives you three methods for traffic routing: failover,
  performance, or weighted round-robin. Choose the one that&rsquo;s right for your
  application or scenario.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Endpoints
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-traffic-manager/apis.md
specificationVersion: "0.14"
apis:
- name: TrafficManagerManagementClient - Endpoints Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-patch
  description: Update a Traffic Manager endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com//
  tags: Traffic, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-patch-openapi.md
- name: TrafficManagerManagementClient - Endpoints Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-get
  description: Gets a Traffic Manager endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com//
  tags: Traffic, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-get-openapi.md
- name: TrafficManagerManagementClient - Endpoints Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-put
  description: Create or update a Traffic Manager endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com//
  tags: Traffic, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-put-openapi.md
- name: TrafficManagerManagementClient - Endpoints Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-delete
  description: Deletes a Traffic Manager endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com//
  tags: Traffic, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.storage.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.traffic.manager.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/traffic-manager/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/traffic-manager/
- type: x-service-level-agreement
  url: https://azure.microsoft.com/en-us/support/legal/sla/traffic-manager/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/traffic-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---