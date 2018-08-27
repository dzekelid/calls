swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/RequestVoiceCall:
    post:
      summary: Add API Requestvoicecall
      description: Add api requestvoicecall.
      operationId: ApiRequestVoiceCallPost
      x-api-path-slug: apirequestvoicecall-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Requestvoicecall