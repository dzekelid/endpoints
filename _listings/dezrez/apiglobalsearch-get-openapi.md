---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez The main endpoint for a global search across all entities in the system.
  version: 1.0.0
  description: The main endpoint for a global search across all entities in the system..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/agency/apikey:
    post:
      summary: Issues an API key for use with the simple role/search endpoints
      description: Issues an api key for use with the simple role/search endpoints.
      operationId: Agency_IssueApiKeyBysubjectId
      x-api-path-slug: apiagencyapikey-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: subjectId
        description: The Id of the group to assign a key to
      responses:
        200:
          description: OK
      tags:
      - Issues
      - Keyuse
      - Simple
      - Role
      - Search
      - Endpoints
  /api/agency/updateportalcustomisation:
    put:
      summary: "THIS IS A TEMPORARY ENDPOINT TO Update a portal customisation against
        a brand within a branch.\r\nPLEASE NOTE: This will be replaced by a FE Tool
        in future. If not, Security must be improved."
      description: "This is a temporary endpoint to update a portal customisation
        against a brand within a branch.\r\nplease note: this will be replaced by
        a fe tool in future. if not, security must be improved.."
      operationId: Agency_UpdatePortalCustomisationByportalCustomisation
      x-api-path-slug: apiagencyupdateportalcustomisation-put
      parameters:
      - in: body
        name: portalCustomisation
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - THIS
      - IS
      - TEMPORARY
      - ENDPOINT
      - TO
      - ""
      - Portal
      - Customisation
      - Against
      - Brand
      - Within
      - Branch
      - PLEASE
      - 'NOTE:'
      - This
      - Will
      - Be
      - Replaced
      - By
      - FE
      - Tool
      - In
      - Future
      - ""
      - If
      - Not
      - ""
      - Security
      - Must
      - Be
      - Improved
  /api/inboundlead/{todoTaskLeadId}/setleadgroup/{groupId}:
    put:
      summary: Endpoint to update group on inbound lead task
      description: Endpoint to update group on inbound lead task.
      operationId: InboundLead_SetLeadGroupBytodoTaskLeadIdBygroupId
      x-api-path-slug: apiinboundleadtodotaskleadidsetleadgroupgroupid-put
      parameters:
      - in: path
        name: groupId
        description: Group Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: todoTaskLeadId
        description: Todos Task Id
      responses:
        200:
          description: OK
      tags:
      - Endpoint
      - To
      - Update
      - Group
      - "On"
      - Inbound
      - Lead
      - Task
  /api/property/bookvaluation:
    post:
      summary: A command driven endpoint to Book a Valuation.
      description: A command driven endpoint to book a valuation..
      operationId: Property_BookValuationBybookValuationData
      x-api-path-slug: apipropertybookvaluation-post
      parameters:
      - in: body
        name: bookValuationData
        description: A wrapper for the various data contracts needed
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - A
      - Command
      - Driven
      - Endpoint
      - To
      - Book
      - Valuation
  /api/property/recordvaluation:
    post:
      summary: A command driven endpoint to Record a Valuation.
      description: A command driven endpoint to record a valuation..
      operationId: Property_RecordValuationByrecordValuationData
      x-api-path-slug: apipropertyrecordvaluation-post
      parameters:
      - in: body
        name: recordValuationData
        description: A wrapper for the various data contracts needed
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - A
      - Command
      - Driven
      - Endpoint
      - To
      - Record
      - Valuation
  /api/property/{id}/updateaddress:
    put:
      summary: A command driven endpoint to Update a property address.
      description: A command driven endpoint to update a property address..
      operationId: Property_UpdateAddressByidByaddressDataContract
      x-api-path-slug: apipropertyidupdateaddress-put
      parameters:
      - in: body
        name: addressDataContract
        description: The address data
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The id of the property
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - A
      - Command
      - Driven
      - Endpoint
      - To
      - ""
      - Property
      - Address
  /api/property/updatevaluation:
    put:
      summary: A command driven endpoint to Update a Valuation.
      description: A command driven endpoint to update a valuation..
      operationId: Property_UpdateValuationByvaluationDataContract
      x-api-path-slug: apipropertyupdatevaluation-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: valuationDataContract
        description: The valuation data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - A
      - Command
      - Driven
      - Endpoint
      - To
      - ""
      - Valuation
  /api/viewing/{id}/delete:
    delete:
      summary: Endpoint to complete the multi viewing container once individual appointments
        have been booked.
      description: Endpoint to complete the multi viewing container once individual
        appointments have been booked..
      operationId: Viewing_CompleteMultiViewingBookingByid
      x-api-path-slug: apiviewingiddelete-delete
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Endpoint
      - To
      - Complete
      - Multi
      - Viewing
      - Container
      - Once
      - Individual
      - Appointments
      - Have
      - Been
      - Booked
  /api/GlobalSearch:
    get:
      summary: The main endpoint for a global search across all entities in the system.
      description: The main endpoint for a global search across all entities in the
        system..
      operationId: GlobalSearch_IndexBytermByexcludeDeletedByexcludeArchivedBylastUpdated
      x-api-path-slug: apiglobalsearch-get
      parameters:
      - in: query
        name: excludeArchived
      - in: query
        name: excludeDeleted
      - in: query
        name: lastUpdated
        description: Get results from the last updated date
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: term
        description: Search term
      responses:
        200:
          description: OK
      tags:
      - The
      - Main
      - Endpointa
      - Global
      - Search
      - Across
      - ""
      - Entities
      - In
      - System
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