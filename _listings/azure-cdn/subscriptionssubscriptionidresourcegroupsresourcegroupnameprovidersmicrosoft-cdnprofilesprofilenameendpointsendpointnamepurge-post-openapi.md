---
swagger: "2.0"
x-collection-name: Azure CDN
x-complete: 0
info:
  title: Azure CDN API Endpoints Purge Content
  description: Removes a content from CDN.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints:
    get:
      summary: Endpoints List By Profile
      description: Lists existing CDN endpoints.
      operationId: Endpoints_ListByProfile
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}
  : get:
      summary: Endpoints Get
      description: Gets an existing CDN endpoint with the specified endpoint name
        under the specified subscription, resource group and profile.
      operationId: Endpoints_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
    put:
      summary: Endpoints Create
      description: Creates a new CDN endpoint with the specified endpoint name under
        the specified subscription, resource group and profile.
      operationId: Endpoints_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put
      parameters:
      - in: body
        name: endpoint
        description: Endpoint properties
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
    patch:
      summary: Endpoints Update
      description: Updates an existing CDN endpoint with the specified endpoint name
        under the specified subscription, resource group and profile. Only tags and
        Origin HostHeader can be updated after creating an endpoint. To update origins,
        use the Update Origin operation. To update custom domains, use the Update
        Custom Domain operation.
      operationId: Endpoints_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: body
        name: endpointUpdateProperties
        description: Endpoint update properties
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
    delete:
      summary: Endpoints Delete
      description: Deletes an existing CDN endpoint with the specified endpoint name
        under the specified subscription, resource group and profile.
      operationId: Endpoints_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/start
  : post:
      summary: Endpoints Start
      description: Starts an existing CDN endpoint that is on a stopped state.
      operationId: Endpoints_Start
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/stop
  : post:
      summary: Endpoints Stop
      description: Stops an existing running CDN endpoint.
      operationId: Endpoints_Stop
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/purge
  : post:
      summary: Endpoints Purge Content
      description: Removes a content from CDN.
      operationId: Endpoints_PurgeContent
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post
      parameters:
      - in: body
        name: contentFilePaths
        description: The path to the content to be purged
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/load
  : post:
      summary: Endpoints Load Content
      description: Pre-loads a content to CDN. Available for Verizon Profiles.
      operationId: Endpoints_LoadContent
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post
      parameters:
      - in: body
        name: contentFilePaths
        description: The path to the content to be loaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/checkResourceUsage
  : post:
      summary: Endpoints List Resource Usage
      description: Checks the quota and usage of geo filters and custom domains under
        the given endpoint.
      operationId: Endpoints_ListResourceUsage
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/origins
  : get:
      summary: Origins List By Endpoint
      description: Lists all of the existing origins within an endpoint.
      operationId: Origins_ListByEndpoint
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---