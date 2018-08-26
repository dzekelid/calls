---
swagger: "2.0"
x-collection-name: SalesLoft
x-complete: 1
info:
  title: SalesLoft
  description: salesloft-helps-transform-sales-teams-into-modern-sales-organizations---converting-more-target-accounts-into-customer-accounts
  version: v2
host: api.salesloft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/activities/calls.json:
    get:
      summary: List calls
      description: |-
        Fetches multiple call records. The records can be filtered, paged, and sorted according to
        the respective parameters.
      operationId: v2.activities.calls.json.get
      x-api-path-slug: v2activitiescalls-json-get
      parameters:
      - in: query
        name: ids
        description: IDs of calls to fetch
      - in: query
        name: include_paging_counts
        description: Whether to include total_pages and total_count in the metadata
      - in: query
        name: page
        description: The current page to fetch results from
      - in: query
        name: per_page
        description: How many records to show per page in the range [1, 100]
      - in: query
        name: sort_by
        description: 'Key to sort on, must be one of: created_at, updated_at'
      - in: query
        name: sort_direction
        description: 'Direction to sort in, must be one of: ASC, DESC'
      - in: query
        name: updated_at
        description: Equality filters that are applied to the updated_at field
      responses:
        200:
          description: OK
      tags:
      - Sales
      - List
      - Calls
  /v2/action_details/call_instructions.json:
    get:
      summary: List call instructions
      description: |-
        Fetches multiple call instruction records. The records can be filtered, paged, and sorted according to
        the respective parameters.
      operationId: v2.action_details.call_instructions.json.get
      x-api-path-slug: v2action-detailscall-instructions-json-get
      parameters:
      - in: query
        name: ids
        description: IDs of call instructions to fetch
      - in: query
        name: include_paging_counts
        description: Whether to include total_pages and total_count in the metadata
      - in: query
        name: page
        description: The current page to fetch results from
      - in: query
        name: per_page
        description: How many records to show per page in the range [1, 100]
      - in: query
        name: sort_by
        description: 'Key to sort on, must be one of: created_at, updated_at'
      - in: query
        name: sort_direction
        description: 'Direction to sort in, must be one of: ASC, DESC'
      responses:
        200:
          description: OK
      tags:
      - Sales
      - List
      - Call
      - Instructions
  /v2/action_details/call_instructions/{id}.json:
    get:
      summary: Fetch a call instructions
      description: Fetches a call instruction, by ID only.
      operationId: v2.action_details.call_instructions.id.json.get
      x-api-path-slug: v2action-detailscall-instructionsid-json-get
      parameters:
      - in: path
        name: id
        description: Call instructions ID
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Fetch
      - Call
      - Instructions
  /v2/activities/calls/{id}.json:
    get:
      summary: Fetch a call
      description: Fetches a call, by ID only.
      operationId: v2.activities.calls.id.json.get
      x-api-path-slug: v2activitiescallsid-json-get
      parameters:
      - in: path
        name: id
        description: Call ID
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Fetch
      - Call
  /v2/call_data_records.json:
    get:
      summary: List call data records
      description: |-
        Fetches multiple call data records. The records can be filtered, paged, and sorted according to
        the respective parameters.

        Call data records are records of all inbound and outbound calls through SalesLoft. A call data record may
        be associated with a call, but does not have to be.
      operationId: v2.call_data_records.json.get
      x-api-path-slug: v2call-data-records-json-get
      parameters:
      - in: query
        name: has_call
        description: Return only call data records which have or do not have a call
          logged for them
      - in: query
        name: ids
        description: IDs of call data records to fetch
      - in: query
        name: include_paging_counts
        description: Whether to include total_pages and total_count in the metadata
      - in: query
        name: page
        description: The current page to fetch results from
      - in: query
        name: per_page
        description: How many records to show per page in the range [1, 100]
      - in: query
        name: sort_by
        description: 'Key to sort on, must be one of: created_at, updated_at'
      - in: query
        name: sort_direction
        description: 'Direction to sort in, must be one of: ASC, DESC'
      - in: query
        name: updated_at
        description: Equality filters that are applied to the updated_at field
      responses:
        200:
          description: OK
      tags:
      - Sales
      - List
      - Call
      - Data
      - Records
  /v2/call_data_records/{id}.json:
    get:
      summary: Fetch a call data record
      description: Fetches a call data record, by ID only.
      operationId: v2.call_data_records.id.json.get
      x-api-path-slug: v2call-data-recordsid-json-get
      parameters:
      - in: path
        name: id
        description: CallDataRecord ID
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Fetch
      - Call
      - Data
      - Record
---