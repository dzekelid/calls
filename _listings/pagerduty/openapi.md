---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 1
info:
  title: PagerDuty
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oncalls:
    get:
      summary: List all of the on-calls
      description: List the on-call entries during a given time range.
      operationId: list-the-oncall-entries-during-a-given-time-range
      x-api-path-slug: oncalls-get
      parameters:
      - in: query
        name: earliest
        description: This will filter on-calls such that only the earliest on-call
          for each combination of escalation policy, escalation level, and user is
          returned
      - in: query
        name: escalation_policy_ids[]
        description: Filters the results, showing only on-calls for the specified
          escalation policy IDs
      - in: query
        name: include[]
        description: Array of additional details to include
      - in: query
        name: No Name
      - in: query
        name: schedule_ids[]
        description: Filters the results, showing only on-calls for the specified
          schedule IDs
      - in: query
        name: since
        description: The start of the time range over which you want to search
      - in: query
        name: until
        description: The end of the time range over which you want to search
      - in: query
        name: user_ids[]
        description: Filters the results, showing only on-calls for the specified
          user IDs
      responses:
        200:
          description: OK
      tags:
      - Oncalls
---