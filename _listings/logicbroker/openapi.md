swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 1
info:
  title: CommerceAPI
  version: 1.0.0
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Webhooks/{WebhookId}/Test:
    get:
      summary: Test a webhook endpoint.
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Webhook_TestWebhook
      x-api-path-slug: apiv1webhookswebhookidtest-get
      parameters:
      - in: query
        name: LogicbrokerKey
        description: The key for a test document
      - in: path
        name: WebhookId
        description: The webhook id
      responses:
        200:
          description: OK
      tags:
      - Test
      - Webhook
      - Endpoint