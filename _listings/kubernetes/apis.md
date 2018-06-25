---
name: Kubernetes
x-slug: kubernetes
description: Manage a cluster of Linux containers as a single system to accelerate
  Dev and simplify Ops. Kubernetes is an open source orchestration system for Docker
  containers. It handles scheduling onto nodes in a compute cluster and actively manages
  workloads to ensure that their state matches the users declared intentions. Using
  the concepts of labels and pods, it groups the containers which make up an application
  into logical units for easy management and discovery.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Endpoints
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apis.md
specificationVersion: "0.14"
apis:
- name: Kubernetes Get Endpoints
  x-api-slug: kubernetes
  description: List objects of kind endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/endpoints
  tags: Endpoints
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3endpoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3endpoints-get-openapi.md
- name: Kubernetes Get Namespaces Endpoints
  x-api-slug: kubernetes
  description: List objects of kind endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/endpoints
  tags: Namespaces,Endpoints
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3namespacesnamespacesendpoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3namespacesnamespacesendpoints-get-openapi.md
- name: Kubernetes Post Namespaces Endpoints
  x-api-slug: kubernetes
  description: Create a endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/endpoints
  tags: Namespaces,Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3namespacesnamespacesendpoints-post-openapi.md
- name: Kubernetes Get Namespaces Endpoints Name
  x-api-slug: kubernetes
  description: Read the specified endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/endpoints/{name}
  tags: Namespaces,Endpoints,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3namespacesnamespacesendpointsname-get-openapi.md
- name: Kubernetes Put Namespaces Endpoints Name
  x-api-slug: kubernetes
  description: Update the specified endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/namespaces/{namespaces}/endpoints/{name}
  tags: Namespaces,Endpoints,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3namespacesnamespacesendpointsname-put-openapi.md
- name: Kubernetes Get Watch Endpoints
  x-api-slug: kubernetes
  description: Watch a list of endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/endpoints
  tags: Watch,Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3watchendpoints-get-openapi.md
- name: Kubernetes Get Watch Namespaces Endpoints
  x-api-slug: kubernetes
  description: Watch a list of endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/namespaces/{namespaces}/endpoints
  tags: Watch,Namespaces,Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacesendpoints-get-openapi.md
- name: Kubernetes Get Watch Namespaces Endpoints Name
  x-api-slug: kubernetes
  description: Watch a particular endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443//api/v1beta3/watch/namespaces/{namespaces}/endpoints/{name}
  tags: Watch,Namespaces,Endpoints,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacesendpointsname-get-openapi.md
- name: Kubernetes
  x-api-slug: kubernetes
  description: Manage a cluster of Linux containers as a single system to accelerate
    Dev and simplify Ops. Kubernetes is an open source orchestration system for Docker
    containers. It handles scheduling onto nodes in a compute cluster and actively
    manages workloads to ensure that their state matches the users declared intentions.
    Using the concepts of labels and pods, it groups the containers which make up
    an application into logical units for easy management and discovery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/endpoints/master/_listings/kubernetes/openapi.md
x-common:
- type: x-blog
  url: http://blog.kubernetes.io/
- type: x-blog-rss
  url: http://blog.kubernetes.io/feeds/posts/default
- type: x-github
  url: https://github.com/kubernetes
- type: x-twitter
  url: https://twitter.com/kubernetesio
- type: x-website
  url: http://kubernetes.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---