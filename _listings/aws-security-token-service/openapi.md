swagger: "2.0"
x-collection-name: AWS Security Token Service
x-complete: 1
info:
  title: AWS Security Token Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetCallerIdentity:
    get:
      summary: Get Caller Identity
      description: |-
        Returns details about the IAM identity whose credentials are used to call the
              API.
      operationId: getCallerIdentity
      x-api-path-slug: actiongetcalleridentity-get
      parameters:
      - in: query
        name: Account
        description: The AWS account ID number of the account that owns or contains
          the calling      entity
        type: string
      - in: query
        name: Arn
        description: The AWS ARN associated with the calling entity
        type: string
      - in: query
        name: UserId
        description: The unique identifier of the calling entity
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity