---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 0
info:
  title: Data2CRM PUT for Call
  description: Update call information
  version: "1"
host: api.data2crm.com:80
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /call:
    get:
      summary: GET for Call
      description: Returns all calls from the system
      operationId: getCallCollection
      x-api-path-slug: call-get
      parameters:
      - in: query
        name: filter
        description: Filter
      - in: query
        name: limit
        description: 'Amount of results (default: 25)'
      - in: query
        name: offset
        description: 'Start from record (default: 0)'
      - in: query
        name: parent_id
        description: Parent Identifier
      - in: query
        name: parent_type
        description: Parent Type
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-DATA-ENABLE
        description: Data Enable
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
    post:
      summary: POST for Call
      description: Add call into the system
      operationId: createCallEntity
      x-api-path-slug: call-post
      parameters:
      - in: body
        name: body
        description: Add call into the system
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
  /call/count:
    get:
      summary: COUNT for Call
      description: Count all calls from the system
      operationId: getCallCountCollection
      x-api-path-slug: callcount-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
      - Count
  /call/describe:
    get:
      summary: DESCRIBE for Call
      description: Returns describe for calls
      operationId: getCallDescribe
      x-api-path-slug: calldescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
      - Describe
  /call/{call_id}:
    delete:
      summary: DELETE for Call
      description: Delete call information
      operationId: deleteCallEntity
      x-api-path-slug: callcall-id-delete
      parameters:
      - in: path
        name: call_id
        description: Call Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
    get:
      summary: GET for Call
      description: Return call information
      operationId: getCallEntity
      x-api-path-slug: callcall-id-get
      parameters:
      - in: path
        name: call_id
        description: Call Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
    put:
      summary: PUT for Call
      description: Update call information
      operationId: updateCallEntity
      x-api-path-slug: callcall-id-put
      parameters:
      - in: body
        name: body
        description: Update call information
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: call_id
        description: Call Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
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