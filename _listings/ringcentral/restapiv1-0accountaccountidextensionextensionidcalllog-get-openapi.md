---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Call Log Records by Filter
  description: "Returns call log records filtered by parameters specified.\nApp Permission\nReadCallLog\nUser
    Permission\nReadCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCLG-110\nParameter [sessionId]
    is not allowed for usage along with parameter [extensionNumber]\n\n\n400\nCMN-101\nParameter
    [transport] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-129\nAccess
    token corrupted\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n401\nOAU-213\nToken
    not found\n\n\n403\nCMN-401\nIn order to call this API endpoint, application needs
    to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn order to call this API
    endpoint, user needs to have [ReadCallLog] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found\n\n\n429\nCMN-301\nRequest rate exceeded"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/active-calls:
    get:
      summary: Get User Active Calls
      description: "Returns records of all extension calls that are in progress, ordered
        by start time in descending order.\nApp Permission\nReadCallLog\nUser Permission\nReadCallLog\nUsage
        Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nCMN-101\nParameter [direction] value is invalid\n\n\n401\nCMN-405\nLogin
        to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn
        order to call this API endpoint, user needs to have [ReadCallLog] permission
        for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
        is not found"
      operationId: listExtensionActiveCalls
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidactivecalls-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: query
        name: direction
        description: The direction for the result records
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: type
        description: Call type of a record
      responses:
        200:
          description: OK
      tags:
      - User
      - Active
      - Calls
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/call-log:
    get:
      summary: Get Call Log Records by Filter
      description: "Returns call log records filtered by parameters specified.\nApp
        Permission\nReadCallLog\nUser Permission\nReadCallLog\nUsage Plan Group\nHeavy\nError
        Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCLG-110\nParameter
        [sessionId] is not allowed for usage along with parameter [extensionNumber]\n\n\n400\nCMN-101\nParameter
        [transport] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-129\nAccess
        token corrupted\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n401\nOAU-213\nToken
        not found\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
        needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn order to call
        this API endpoint, user needs to have [ReadCallLog] permission for requested
        resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is not found\n\n\n429\nCMN-301\nRequest
        rate exceeded"
      operationId: loadExtensionCallLog
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidcalllog-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: query
        name: dateFrom
        description: The start datetime for resulting records in ISO 8601 format including
          timezone, for example 2016-03-10T18:07:52
      - in: query
        name: dateTo
        description: The end datetime for resulting records in ISO 8601 format including
          timezone, for example 2016-03-10T18:07:52
      - in: query
        name: direction
        description: The direction for the resulting records
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: query
        name: extensionNumber
        description: Extension number of a user
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: phoneNumber
        description: Phone number of a caller/callee
      - in: query
        name: sessionId
      - in: query
        name: showBlocked
        description: If True then calls from/to blocked numbers are returned
      - in: query
        name: transport
        description: Call transport type
      - in: query
        name: type
        description: Call type of a record
      - in: query
        name: view
        description: The default value is Simple for both account and extension call
          log
      - in: query
        name: withRecording
        description: True should be specified to return recorded calls only
      responses:
        200:
          description: OK
      tags:
      - Call
      - Log
      - Records
      - By
      - Filter
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/call-log/{callRecordId}:
    get:
      summary: Get Call Records by ID
      description: "Returns filtered call log records.\nApp Permission\nReadCallLog\nUser
        Permission\nReadCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
        Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to
        call this API endpoint, application needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn
        order to call this API endpoint, user needs to have [ReadCallLog] permission
        for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
        is not found"
      operationId: getCallRecords
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: callRecordId
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: query
        name: view
      responses:
        200:
          description: OK
      tags:
      - Call
      - Records
      - By
      - ID
  /restapi/v1.0/account/{accountId}/call-log:
    get:
      summary: Get Call Log Records by Filter
      description: "Returns call log records filtered by parameters specified.\nApp
        Permission\nReadCallLog\nUser Permission\nFullCompanyCallLog\nUsage Plan Group\nHeavy\nError
        Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCLG-110\nParameter
        [sessionId] is not allowed for usage along with parameter [extensionNumber]\n\n\n400\nCMN-101\nParameter
        [dateFrom] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint,
        application needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn order
        to call this API endpoint, user needs to have [ReadCompanyCallLog] permission
        for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
        is not found"
      operationId: loadAccountCallLog
      x-api-path-slug: restapiv1-0accountaccountidcalllog-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: query
        name: dateFrom
        description: The start datetime for resulting records in ISO 8601 format including
          timezone, for example 2016-03-10T18:07:52
      - in: query
        name: dateTo
        description: The end datetime for resulting records in ISO 8601 format including
          timezone, for example 2016-03-10T18:07:52
      - in: query
        name: direction
        description: The direction for the result records
      - in: query
        name: extensionNumber
        description: Extension number of a user
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: phoneNumber
        description: Phone number of a caller/call recipient
      - in: query
        name: sessionId
      - in: query
        name: type
        description: Call type of a record
      - in: query
        name: view
        description: The default value is Simple for both account and extension call
          log
      - in: query
        name: withRecording
        description: True if only recorded calls have to be returned
      responses:
        200:
          description: OK
      tags:
      - Call
      - Log
      - Records
      - By
      - Filter
  /restapi/v1.0/account/{accountId}/recording/{recordingId}:
    get:
      summary: Get Call Recordings
      description: "Returns call recording metadata by ID.\nApp Permission\nReadCallRecording\nUser
        Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n
        \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
        to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadCallRecording]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
      operationId: listCallRecordings
      x-api-path-slug: restapiv1-0accountaccountidrecordingrecordingid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: recordingId
        description: Internal identifier of a recording (returned in Call Log)
      responses:
        200:
          description: OK
      tags:
      - Call
      - Recordings
  /restapi/v1.0/account/{accountId}/recording/{recordingId}/content:
    get:
      summary: Get Call Recordings Data
      description: "Returns media content of a call recording.\nApp Permission\nReadCallRecording\nUser
        Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n
        \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
        Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
        access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadCallRecording]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found\n\n\n416\nCMN-107\nRequested
        range not satisfiable"
      operationId: listCallRecordingData
      x-api-path-slug: restapiv1-0accountaccountidrecordingrecordingidcontent-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: recordingId
        description: Internal identifier of a recording (returned in Call Log)
      responses:
        200:
          description: OK
      tags:
      - Call
      - Recordings
      - Data
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/ring-out:
    post:
      summary: Make RingOut Call
      description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
        Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nCMN-101\nParameter [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller
        ID: [+18609411729] is not allowed\n\n\n400\nTEL-108\nphoneNumber specified
        in the from field is empty or invalid\n\n\n400\nTEL-109\nphoneNumber specified
        in the to field is empty or invalid\n\n\n403\nBIL-103\nFeature [RingOut] is
        not available for current account\n\n\n403\nCMN-112\nFeature [RingOut] is
        not available for current extension type\n\n\n403\nCMN-113\nFeature [DomesticCalls]
        is not available for current extension\n\n\n403\nRNG-102\nCaller ID should
        be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber specified
        in the to field: [17176704078] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
        specified in the from field: [17176704078] is in blocked list\n\n\n403\nTEL-107\nCaller
        ID: [+12094441763] is not allowed\n\n\n404\nCMN-102\nResource for parameter
        [forwardingNumberId] is not found"
      operationId: makeRingOutCallNew
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidringout-post
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Make
      - RingOut
      - Call
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/ring-out/{ringoutId}:
    get:
      summary: Get Status of RingOut Call
      description: "Returns the status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
        Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n503\nCMN-201\nService Temporary Unavailable"
      operationId: getRingOutCallStatusNew
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: ringoutId
        description: Internal identifier of a RingOut call
      responses:
        200:
          description: OK
      tags:
      - Status
      - Of
      - RingOut
      - Call
    delete:
      summary: Cancel RingOut Call
      description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
        Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n404\nCMN-102\nResource for parameter [ringOutId] is not
        found"
      operationId: cancelRingOutCallNew
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: ringoutId
        description: Internal identifier of a RingOut call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - RingOut
      - Call
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/ringout:
    post:
      summary: Make RingOut Call
      description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
        Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nCMN-101\nParameter [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller
        ID: [+14152961727] is not allowed\n\n\n400\nTEL-108\nphoneNumber specified
        in the from field is empty or invalid\n\n\n400\nTEL-109\nphoneNumber specified
        in the to field is empty or invalid\n\n\n403\nBIL-103\nFeature [RingOut] is
        not available for current account\n\n\n403\nCMN-112\nFeature [RingOut] is
        not available for current extension type\n\n\n403\nCMN-113\nFeature [DomesticCalls]
        is not available for current extension\n\n\n403\nCMN-401\nIn order to call
        this API endpoint, application needs to have [RingOut] permission\n\n\n403\nRNG-102\nCaller
        ID should be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber
        specified in the to field: [17176704073] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
        specified in the from field: [17172302150] is in blocked list\n\n\n403\nTEL-107\nCaller
        ID: [+12094441789] is not allowed\n\n\n404\nCMN-102\nResource for parameter
        [extensionId] is not found"
      operationId: makeRingOutCall
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidringout-post
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Make
      - RingOut
      - Call
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/ringout/{ringoutId}:
    get:
      summary: Get Status of RingOut Call
      description: "Returns status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
        Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint,
        application needs to have [RingOut] permission\n\n\n404\nCMN-102\nResource
        for parameter [extensionId] is not found"
      operationId: getRingOutCallStatus
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: ringoutId
        description: Internal identifier of a RingOut call
      responses:
        200:
          description: OK
      tags:
      - Status
      - Of
      - RingOut
      - Call
    delete:
      summary: Cancel RingOut Call
      description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
        Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n404\nCMN-102\nResource for parameter [extensionId] is not
        found"
      operationId: cancelRingOutCall
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: ringoutId
        description: Internal identifier of a RingOut call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - RingOut
      - Call
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/answering-rule:
    get:
      summary: Get Call Handling Rules
      description: "Returns the extension answering rules.\nApp Permission\nReadAccounts\nUser
        Permission\nReadUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint,
        application needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn
        order to call this API endpoint, user needs to have [ReadUserAnsweringRules]
        permission for requested resource.\n\n\n404\nCMN-102\nResource for parameter
        [accountId] is not found"
      operationId: loadAnsweringRulesList
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: query
        name: page
      - in: query
        name: perPage
      responses:
        200:
          description: OK
      tags:
      - Call
      - Handling
      - Rules
    post:
      summary: Create Custom Call Handling Rules
      description: "Creates a custom answering rule for a particular caller ID.\nApp
        Permission\nEditExtensions\nUser Permission\nEditUserAnsweringRules\nUsage
        Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nAWR-100\nRule indexes should be sequential\n\n\n400\nAWR-101\nParameter
        [forwarding.rules[].forwardingNumbers[].id] are duplicated\n\n\n400\nAWR-106\nGreeting
        [Voicemail] is duplicated\n\n\n400\nAWR-107\nMore than one caller with the
        same [callerId]\n\n\n400\nAWR-108\nOnly custom rule can be created\n\n\n400\nAWR-111\nAt
        least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
        number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-121\nBusiness
        Hours not specified for current user\n\n\n400\nAWR-123\nPreset [131840] can
        not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId specified
        for greeting type [Voicemail] is not found\n\n\n400\nAWR-125\nCustom greeting
        presetId specified for greeting type [Introductory]. Custom greeting uploading
        method should be used\n\n\n400\nAWR-126\nThe amount of schedule ranges exceeds
        1000\n\n\n400\nAWR-136\nRing group with index 1 is not found\n\n\n400\nAWR-137\nRule
        index should be greater than 0\n\n\n400\nAWR-138\nContact center number cannot
        be used as called number\n\n\n400\nAWR-139\nHold audio interruption period
        not specified\n\n\n400\nAWR-140\nHold audio interruption period should be
        empty for interruption mode specified\n\n\n400\nAWR-144\nCall Queue agent
        with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not be used
        for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
        be the same as call queue members\n\n\n400\nAWR-149\nOnly user, voicemail
        or shared line group extension can be a voicemail recipient\n\n\n400\nAWR-150\nOnly
        user, voicemail, shared line group extension or current department can be
        a voicemail recipient\n\n\n400\nAWR-152\nVoicemail cannot be turned off for
        call queue extension\n\n\n400\nAWR-177\nTime ranges limit for [monday] exceeded\n\n\n400\nAWR-179\n[name]
        is too long: up to 127 symbols supported\n\n\n400\nCMN-101\nParameter [name]
        value is invalid\n\n\n400\nFPN-105\nNumber +16196093249 duplicates with company/extension
        direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [EditExtensions]
        permission\n\n\n403\nCMN-408\nIn order to call this API endpoint, user needs
        to have [EditUserAnsweringRules] permission for requested resource.\n\n\n404\nCMN-102\nResource
        for parameter [accountId] is not found"
      operationId: createAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-post
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Call
      - Handling
      - Rules
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/answering-rule/{ruleId}:
    get:
      summary: Get Call Handling Rule
      description: "Returns an answering rule by ID.\nApp Permission\nReadAccounts\nUser
        Permission\nReadUserAnsweringRules\nUsage Plan Group\nLight\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [showInactiveNumbers] value is invalid\n\n\n403\nCMN-401\nIn order to call
        this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
        for parameter [answering-rule] is not found"
      operationId: loadAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: ruleId
        description: Internal identifier of an answering rule
      - in: query
        name: showInactiveNumbers
        description: Indicates whether invactive numbers should be returned or not
      responses:
        200:
          description: OK
      tags:
      - Call
      - Handling
      - Rule
    put:
      summary: Update Custom Call Handling Rule
      description: "Updates a custom answering rule for a particular caller ID.\nApp
        Permission\nEditExtensions\nUser Permission\nEditUserAnsweringRules\nUsage
        Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nAWR-100\nRule indexes should be sequential\n\n\n400\nAWR-106\nGreeting
        [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt least one condition should
        be specified\n\n\n400\nAWR-113\nMore than one called number with the same
        [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After Hours
        schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
        [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
        specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing
        group with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater
        than 0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
        audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
        period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
        Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can
        not be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue
        agents should be the same as call queue members\n\n\n400\nAWR-179\n[name]
        is too long: up to 127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction]
        value is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
        direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [EditExtensions]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
      operationId: updateAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: ruleId
        description: Internal identifier of an answering rule
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Call
      - Handling
      - Rule
    delete:
      summary: Delete Call Handling Rule
      description: "Deletes a custom answering rule by a particular ID.\nApp Permission\nEditExtensions\nUser
        Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nAWR-110\nBusiness
        Hours/After Hours rule cannot be deleted\n\n\n403\nCMN-401\nIn order to call
        this API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
        order to call this API endpoint, user needs to have [EditUserAnsweringRules]
        permission for requested resource.\n\n\n404\nCMN-102\nResource for parameter
        [answering-rule] is not found"
      operationId: deleteAnsweringRule
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: ruleId
        description: Internal identifier of an answering rule
      responses:
        200:
          description: OK
      tags:
      - Call
      - Handling
      - Rule
  /restapi/v1.0/account/{accountId}/answering-rule:
    post:
      summary: Create Company Call Handling Rule
      description: "Creates a company answering rule for a particular caller ID.\nApp
        Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage
        Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
        custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
        condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
        Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
        preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension]
        must be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
        can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
        is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
        is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
        value is invalid"
      operationId: createCompanyAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidansweringrule-post
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Company
      - Call
      - Handling
      - Rule
    get:
      summary: Get Company Call Handling Rules
      description: |-
        Returns a list of company answering rules.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyAnsweringRules
        Usage Plan Group
        Medium
      operationId: listCompanyAnsweringRule
      x-api-path-slug: restapiv1-0accountaccountidansweringrule-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Company
      - Call
      - Handling
      - Rules
  /restapi/v1.0/account/{accountId}/answering-rule/{ruleId}:
    get:
      summary: Get Company Call Handling Rule
      description: |-
        Returns a company answering rule by ID.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyAnsweringRules
        Usage Plan Group
        Light
      operationId: loadCompanyAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidansweringruleruleid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: ruleId
        description: Internal identifier of an answering rule
      responses:
        200:
          description: OK
      tags:
      - Company
      - Call
      - Handling
      - Rule
    put:
      summary: Update Company Call Handling Rule
      description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
        Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
        type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with
        [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must be specified
        for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension] can be specified
        for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name] is too long:
        up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action is available
        in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
        value is invalid"
      operationId: updateCompanyAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidansweringruleruleid-put
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: ruleId
        description: Internal identifier of an answering rule
      responses:
        200:
          description: OK
      tags:
      - Company
      - Call
      - Handling
      - Rule
  /restapi/v1.0/account/{accountId}/call-recording:
    get:
      summary: Get Call Recording Settings
      description: |-
        Returns call recording settings.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyInfo
        Usage Plan Group
        Light
      operationId: loadCallRecordingSettings
      x-api-path-slug: restapiv1-0accountaccountidcallrecording-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - Call
      - Recording
      - Settings
  /restapi/v1.0/account/{accountId}/call-recording/extensions:
    get:
      summary: Get Call Recording Extension Settings
      description: |-
        Returns the list of extensions to be recorded.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyInfo
        Usage Plan Group
        Medium
      operationId: listCallRecordingExtensionSettings
      x-api-path-slug: restapiv1-0accountaccountidcallrecordingextensions-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - Call
      - Recording
      - Extension
      - Settings
  /restapi/v1.0/account/{accountId}/call-recording/custom-greetings:
    get:
      summary: '[Beta] Get Call Recording Custom Greetings'
      description: |-
        Returns call recording custom greetings.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyInfo
        Usage Plan Group
        Medium
      operationId: listCallRecordingCustomGreetings
      x-api-path-slug: restapiv1-0accountaccountidcallrecordingcustomgreetings-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - '[Beta]'
      - ""
      - Call
      - Recording
      - Custom
      - Greetings
  /restapi/v1.0/account/{accountId}/department/bulk-assign:
    post:
      summary: Edit Call Queue Members
      description: "[Deprecated] Adds and/or removes multiple call queue members\nApp
        Permission\nEditAccounts\nUser Permission\nUserGroups\nUsage Plan Group\nHeavy\nError
        Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nEXT-401\nExtension
        ID should be present only in one section"
      operationId: bulkAssignDepartments
      x-api-path-slug: restapiv1-0accountaccountiddepartmentbulkassign-post
      parameters:
      - in: path
        name: accountId
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Call
      - Queue
      - Members
  /restapi/v1.0/account/{accountId}/call-queues:
    get:
      summary: Get Call Queues
      description: |-
        Returns call queue group list
        App Permission
        ReadAccounts
        User Permission
        ReadExtensions
        Usage Plan Group
        Medium
      operationId: listCallQueues
      x-api-path-slug: restapiv1-0accountaccountidcallqueues-get
      parameters:
      - in: path
        name: accountId
      - in: query
        name: memberExtensionId
        description: Internal identifier of an extension that is a member of every
          group within the result
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      responses:
        200:
          description: OK
      tags:
      - Call
      - Queues
  /restapi/v1.0/account/{accountId}/call-queues/{groupId}/members:
    get:
      summary: Get Call Queue Members
      description: |-
        Returns call queue group members.
        App Permission
        ReadAccounts
        User Permission
        ReadExtensions
        Usage Plan Group
        Light
      operationId: listCallQueueMembers
      x-api-path-slug: restapiv1-0accountaccountidcallqueuesgroupidmembers-get
      parameters:
      - in: path
        name: accountId
      - in: path
        name: groupId
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      responses:
        200:
          description: OK
      tags:
      - Call
      - Queue
      - Members
  /restapi/v1.0/account/{accountId}/call-queues/{groupId}/bulk-assign:
    post:
      summary: Edit Call Queue Group
      description: "Updates call queue group.\nApp Permission\nEditExtensions\nUser
        Permission\nGroups\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
        Code\n   Error Code\n   Error Message\n   \n \n\n400\nEXT-405\nExtension of
        type [ParkLocation] could not be a member of [department}]"
      operationId: updateCallQueueGroup
      x-api-path-slug: restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post
      parameters:
      - in: path
        name: accountId
      - in: body
        name: body
        description: Changes for the given group
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: groupId
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Call
      - Queue
      - Group
  /restapi/v1.0/account/{accountId}/call-monitoring-groups:
    get:
      summary: Get Call Monitoring Groups
      description: |-
        Returns call monitoring groups that can be filtered by some extension.
        App Permission
        ReadAccounts
        User Permission
        ReadExtensions
        Usage Plan Group
        Medium
      operationId: listCallMonitoringGroups
      x-api-path-slug: restapiv1-0accountaccountidcallmonitoringgroups-get
      parameters:
      - in: path
        name: accountId
      - in: query
        name: memberExtensionId
        description: Internal identifier of an extension that is a member of every
          group within the result
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      responses:
        200:
          description: OK
      tags:
      - Call
      - Monitoring
      - Groups
  /restapi/v1.0/account/{accountId}/call-monitoring-groups/{groupId}/members:
    get:
      summary: Get Call Monitoring Group Members
      description: |-
        Returns call monitoring group members.
        App Permission
        ReadAccounts
        User Permission
        ReadExtensions
        Usage Plan Group
        Medium
      operationId: listCallMonitoringGroupMembers
      x-api-path-slug: restapiv1-0accountaccountidcallmonitoringgroupsgroupidmembers-get
      parameters:
      - in: path
        name: accountId
      - in: path
        name: groupId
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      responses:
        200:
          description: OK
      tags:
      - Call
      - Monitoring
      - Group
      - Members
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