---
name: AWS Security Token Service
x-slug: aws-security-token-service
description: The AWS Security Token Service (STS) is a web service that enables you
  to request temporary, limited-privilege credentials for AWS Identity and Access
  Management (IAM) users or for users that you authenticate (federated users).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Calls
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/aws-security-token-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Security Token Service API - Get Caller Identity
  x-api-slug: actiongetcalleridentity-get
  description: |-
    Returns details about the IAM identity whose credentials are used to call the
          API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: :///
  tags: Amazon Web Services, Authentication, Security, Stack Network, API Service
    Provider, API Service Provider, API Provider, Profiles, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/aws-security-token-service/actiongetcalleridentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/aws-security-token-service/actiongetcalleridentity-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.s3.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.security.token.service.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/STS/latest/APIReference/
- type: x-errors
  url: http://docs.aws.amazon.com/STS/latest/APIReference/CommonErrors.html
- type: x-website
  url: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---