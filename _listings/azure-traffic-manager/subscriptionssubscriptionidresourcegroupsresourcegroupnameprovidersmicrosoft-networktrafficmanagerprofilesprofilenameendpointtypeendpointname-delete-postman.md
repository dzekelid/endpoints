{
  "info": {
    "name": "Azure Traffic Manager API Endpoints Delete",
    "_postman_id": "b763fd85-fafb-4899-8b7a-0cc66eac7977",
    "description": "Deletes a Traffic Manager endpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "endpoints",
      "item": [
        {
          "id": "8b226e43-8b1f-4ab8-9a8d-5899d03f62d0",
          "name": "Endpoints_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a Traffic Manager endpoint"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bfef3af7-f9b4-4fa7-a1aa-2323e4282221"
            }
          ]
        }
      ]
    }
  ]
}