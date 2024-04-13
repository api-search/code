---
name: Atlassian
description: >-
  Atlassian Corporation is an Australian software company that develops products
  for software developers, project managers and other software development
  teams.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/atlassian.yml
created: 2023/11/10
modified: 2023/11/10
specificationVersion: '0.16'
tags: []
apis:
  - name: Jira API
    description: >-
      The Jira REST API enables you to interact with Jira programmatically. Use
      this API to build apps, script interactions with Jira, or develop any
      other type of integration. This page documents the REST resources
      available in Jira Cloud, including the HTTP response codes and example
      requests and responses.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/#about
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/#about
      - type: OpenAPI
        url: properties/jira-openapi-original.yml
      - type: Postman Collection
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/jiracloud.3.postman.json
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://dac-static.atlassian.com/cloud/jira/platform/swagger-v3.v3.json?_v=1.6660.0-0.1294.0-openapi-search.yml
      - type: APIs.io Search
        url: overlays/jira-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/jira-openapi-api-evangelist-ratings.yml
    aid: atlassian:jira-api
  - name: Confluence API
    description: >-
      This is the reference for the Confluence Cloud REST API. This API is the
      primary way to get and modify data in Confluence Cloud, whether you are
      developing an app or any other integration. Use it to interact with
      Confluence entities, like pages and blog posts, spaces, users, groups, and
      more.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.atlassian.com/cloud/confluence/rest/v1/intro/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.atlassian.com/cloud/confluence/rest/v1/intro/
      - type: OpenAPI
        url: properties/confluence-openapi-original.yml
      - type: Postman Collection
        url: >-
          https://developer.atlassian.com/cloud/confluence/confcloud.1.postman.json
      - type: Authentication
        url: https://developer.atlassian.com/cloud/confluence/rest/v1/intro/#auth
      - type: Status Codes
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/intro/#status-code
      - type: Capabilities
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/intro/#capabilities
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://dac-static.atlassian.com/cloud/confluence/swagger.v3.json?_v=1.6660.0-0.1294.0-openapi-search.yml
      - type: APIs.io Search
        url: overlays/confluence-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/confluence-openapi-api-evangelist-ratings.yml
    aid: atlassian:confluence-api
  - name: BitBucket API
    description: >-
      The purpose of this section is to describe how to authenticate when making
      API calls using the Bitbucket REST API.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.atlassian.com/cloud/bitbucket/rest/intro/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.atlassian.com/cloud/bitbucket/rest/intro/
      - type: OpenAPI
        url: properties/bitbucket-openapi-original.yml
      - type: Postman Collection
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/bitbucketcloud.postman.json
      - type: Authentication
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/rest/intro/#authentication
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://dac-static.atlassian.com/cloud/bitbucket/swagger.v3.json?_v=2.300.9-0.1294.0-openapi-search.yml
      - type: APIs.io Search
        url: overlays/bitbucket-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bitbucket-openapi-api-evangelist-ratings.yml
    aid: atlassian:bitbucket-api
common:
  - type: Status
    url: https://status.developer.atlassian.com/
  - type: Blog
    url: https://blog.developer.atlassian.com/
  - type: Road Map
    url: https://trello.com/b/z2GIJ3xD/forge-roadmap-for-developers
  - type: Marketplace
    url: https://marketplace.atlassian.com/
  - type: Support
    url: https://developer.atlassian.com/support
  - type: Login
    url: https://id.atlassian.com/login
  - type: Signup
    url: https://id.atlassian.com/signup
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: atlassian
---