swagger: "2.0"
x-collection-name: APImetrics
x-complete: 1
info:
  title: APImetrics Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /calls/:
    get:
      summary: List API Calls
      description: List API Calls
      operationId: listAPICalls
      x-api-path-slug: calls-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
    post:
      summary: Create new API Call
      description: Create new API Call
      operationId: createNewAPICall
      x-api-path-slug: calls-post
      parameters:
      - in: body
        name: Body
        description: '{     meta: {         name: Minimal API test name     },     request:
          {         method: get,         url: http://httpbin'
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
  /calls/auth/{auth_id}/:
    get:
      summary: List API Calls by Authentication
      description: List API Calls by Authentication
      operationId: listAPICallsbyAuthentication
      x-api-path-slug: callsauthauth-id-get
      parameters:
      - in: path
        name: auth_id
        description: The ID of the authentication setting
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
      - Auth
      - Auth
  /calls/{id}/:
    delete:
      summary: Delete an API Call
      description: Delete an API Call
      operationId: deleteAnAPICall
      x-api-path-slug: callsid-delete
      parameters:
      - in: path
        name: id
        description: ID string of API Call
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
    get:
      summary: Get an existing API Call
      description: Get an existing API Call
      operationId: getAnExistingAPICall
      x-api-path-slug: callsid-get
      parameters:
      - in: path
        name: id
        description: ID string of API Call
      - in: query
        name: kind
        description: Granularity of data required, one of DAY, WEEK, MONTH, tYEAR
      - in: query
        name: location_id
        description: Location where the API Call was made
      - in: query
        name: time
        description: ISO formatted date string for the period you wish to view
      - in: query
        name: type
        description: Return stats for all calls in the time period specified which
          had this result
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
    put:
      summary: Update an existing API Call
      description: Update an existing API Call
      operationId: updateAnExistingAPICall
      x-api-path-slug: callsid-put
      parameters:
      - in: body
        name: body
        description: '{     request: {         parameters: [             { key: testing,
          value: bar },             { key: raspberry, value: 2 }         ]     } }'
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID string of API Call
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
  /calls/{id}/run:
    post:
      summary: Trigger an API Call to run
      description: Trigger an API Call to run
      operationId: triggerAnAPICallToRun
      x-api-path-slug: callsidrun-post
      parameters:
      - in: body
        name: body
        description: '{     location_id: ,     context: {         foo: 1234,         bar:
          %%RESULT_ID%%,         datum: %%DATETIME%%     } }'
        schema:
          $ref: '#/definitions/holder'
      - in: formData
        name: context
        description: Dictionary of variable names and their values
      - in: path
        name: id
        description: ID string of API Call
      - in: formData
        name: location_id
        description: Location ID of test agent that will make the request
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
      - ""
      - Run
  /calls/{id}/stats/before:
    get:
      summary: List Stats from before a date for an API Call
      description: List Stats from before a date for an API Call
      operationId: listStatsFromBeforeDateAPICall
      x-api-path-slug: callsidstatsbefore-get
      parameters:
      - in: path
        name: id
        description: ID string of API Call
      - in: query
        name: kind
        description: Granularity of data required, one of DAY, WEEK, MONTH, YEAR
      - in: query
        name: limit
        description: Maximum number of results to return
      - in: query
        name: location_id
        description: Location where the API Call was made
      - in: query
        name: time
        description: ISO formatted date string for the end of the period you wish
          to view
      - in: query
        name: type
        description: Return stats for all calls in the time period specified which
          had this result
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
      - ""
      - Stats
      - Before
  /calls/{id}/stats/since:
    get:
      summary: List Stats since a date for an API Call
      description: List Stats since a date for an API Call
      operationId: listStatsSinceDateAPICall
      x-api-path-slug: callsidstatssince-get
      parameters:
      - in: path
        name: id
        description: ID string of API Call
      - in: query
        name: kind
        description: Granularity of data required, one of DAY, WEEK, MONTH, YEAR
      - in: query
        name: limit
        description: Maximum number of results to return
      - in: query
        name: location_id
        description: Location where the API Call was made
      - in: query
        name: time
        description: ISO formatted date string for the start of the period you wish
          to view
      - in: query
        name: type
        description: Return stats for all calls in the time period specified which
          had this result
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Calls
      - ""
      - Stats
      - Since
  /deployments/call/{call_id}/:
    get:
      summary: Get all Deployments for an API Call
      description: Get all Deployments for an API Call
      operationId: getAllDeploymentForAPICall
      x-api-path-slug: deploymentscallcall-id-get
      parameters:
      - in: path
        name: call_id
        description: ID of the API Call
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Deployments
      - Call
      - Call