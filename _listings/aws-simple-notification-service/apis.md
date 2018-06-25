---
name: AWS Simple Notification Service
x-slug: aws-simple-notification-service
description: Amazon Simple Notification Service (Amazon SNS) is a fast, flexible,
  fully managed push notification service that lets you send individual messages or
  to fan-out messages to large numbers of recipients. Amazon SNS makes it simple and
  cost effective to send push notifications to mobile device users, email recipients
  or even send messages to other distributed services.With Amazon SNS, you can send
  notifications to Apple, Google, Fire OS, and Windows devices, as well as to Android
  devices in China with Baidu Cloud Push. You can use SNS to send SMS messages to
  mobile device users worldwide.Beyond these endpoints, Amazon SNS can also deliver
  messages toAmazon Simple Queue Service(SQS),AWS Lambda functions, or to any HTTP
  endpoint.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Endpoints
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/aws-simple-notification-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Simple Notification Service API Create Platform Endpoint
  x-api-slug: aws-simple-notification-service-api
  description: |-
    Creates an endpoint for a device and mobile app on one of the supported push notification
          services, such as GCM and APNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: ://///?Action=CreatePlatformEndpoint
  tags: Platform Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/aws-simple-notification-service/actioncreateplatformendpoint-get-openapi.md
- name: AWS Simple Notification Service API Delete Endpoint
  x-api-slug: aws-simple-notification-service-api
  description: Deletes the endpoint for a device and mobile app from Amazon SNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: ://///?Action=DeleteEndpoint
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/aws-simple-notification-service/actiondeleteendpoint-get-openapi.md
- name: AWS Simple Notification Service API Get Endpoint Attributes
  x-api-slug: aws-simple-notification-service-api
  description: |-
    Retrieves the endpoint attributes for a device on one of the supported push notification
          services, such as GCM and APNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: ://///?Action=GetEndpointAttributes
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/aws-simple-notification-service/actiongetendpointattributes-get-openapi.md
- name: AWS Simple Notification Service API List Endpoints By Platform Application
  x-api-slug: aws-simple-notification-service-api
  description: |-
    Lists the endpoints and endpoint attributes for devices in a supported push notification
          service, such as GCM and APNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: ://///?Action=ListEndpointsByPlatformApplication
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/aws-simple-notification-service/actionlistendpointsbyplatformapplication-get-openapi.md
- name: AWS Simple Notification Service API Set Endpoint Attributes
  x-api-slug: aws-simple-notification-service-api
  description: |-
    Sets the attributes for an endpoint for a device on one of the supported push notification
          services, such as GCM and APNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: ://///?Action=SetEndpointAttributes
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/aws-simple-notification-service/actionsetendpointattributes-get-openapi.md
- name: AWS Simple Notification Service API Subscribe
  x-api-slug: aws-simple-notification-service-api
  description: Prepares to subscribe an endpoint by sending the endpoint a confirmation
    message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: ://///?Action=Subscribe
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/aws-simple-notification-service/actionsubscribe-get-openapi.md
- name: AWS Simple Notification Service API
  x-api-slug: aws-simple-notification-service-api
  description: Amazon Simple Notification Service (Amazon SNS) is a fast, flexible,
    fully managed push notification service that lets you send individual messages
    or to fan-out messages to large numbers of recipients. Amazon SNS makes it simple
    and cost effective to send push notifications to mobile device users, email recipients
    or even send messages to other distributed services.With Amazon SNS, you can send
    notifications to Apple, Google, Fire OS, and Windows devices, as well as to Android
    devices in China with Baidu Cloud Push. You can use SNS to send SMS messages to
    mobile device users worldwide.Beyond these endpoints, Amazon SNS can also deliver
    messages toAmazon Simple Queue Service(SQS),AWS Lambda functions, or to any HTTP
    endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/aws-simple-notification-service/openapi.md
x-common:
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/Amazon-SN
- type: x-console
  url: https://console.aws.amazon.com/sns
- type: x-documentation
  url: http://docs.aws.amazon.com/sns/latest/api/
- type: x-faq
  url: https://aws.amazon.com/sns/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=72
- type: x-getting-started
  url: https://aws.amazon.com/sns/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/sns/pricing/
- type: x-website
  url: https://aws.amazon.com/sns/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---