---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 1
info:
  title: AWS EC2 API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteVpcEndpoints:
    get:
      summary: Delete Vpc Endpoints
      description: Deletes one or more specified VPC endpoints.
      operationId: deletevpcendpoints
      x-api-path-slug: actiondeletevpcendpoints-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: PrefixListId.N
        description: One or more prefix list IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoints
  /?Action=DescribeVpcEndpoints:
    get:
      summary: Describe Vpc Endpoints
      description: Describes one or more of your VPC endpoints.
      operationId: describevpcendpoints
      x-api-path-slug: actiondescribevpcendpoints-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoints
---