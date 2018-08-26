---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/sync/cronofycallback/{negotiatorId}/{uniqueIdentifier}:
    post:
      summary: Forces a call to get updates from Cronofy for the rezi calendar
      description: Forces a call to get updates from cronofy for the rezi calendar.
      operationId: Sync_CronofyCallbackBynegotiatorIdByuniqueIdentifierBycalendarSyncResyncDataContract
      x-api-path-slug: apisynccronofycallbacknegotiatoriduniqueidentifier-post
      parameters:
      - in: body
        name: calendarSyncResyncDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: negotiatorId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: uniqueIdentifier
      responses:
        200:
          description: OK
      tags:
      - Forces
      - Call
      - To
      - Get
      - Updates
      - From
      - Cronofythe
      - Rezi
      - Calendar
  /api/sync/deletecalendar:
    delete:
      summary: Forces a call to get updates from Cronofy for the rezi calendar
      description: Forces a call to get updates from cronofy for the rezi calendar.
      operationId: Sync_DeleteCalendar
      x-api-path-slug: apisyncdeletecalendar-delete
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Forces
      - Call
      - To
      - Get
      - Updates
      - From
      - Cronofythe
      - Rezi
      - Calendar
---