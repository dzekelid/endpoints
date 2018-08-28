{
  "info": {
    "name": "Azure Traffic Manager API Endpoints Get",
    "_postman_id": "bfbac2e2-fe47-4979-bb03-d554b0bd9796",
    "description": "Gets a Traffic Manager endpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "endpoints",
      "item": [
        {
          "id": "ef00d9be-4473-4435-b6c4-804448d58543",
          "name": "Endpoints_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/trafficmanagerprofiles/:profileName/:endpointType/:endpointName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "endpointName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "endpointType",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "profileName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a Traffic Manager endpoint"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d92cf57-d4a9-4429-b145-0cfda2a3be89"
            }
          ]
        }
      ]
    }
  ]
}