---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Calls
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get User Active Calls
  x-api-slug: restapiv1-0accountaccountidextensionextensionidactivecalls-get
  description: "Returns records of all extension calls that are in progress, ordered
    by start time in descending order.\nApp Permission\nReadCallLog\nUser Permission\nReadCallLog\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [direction] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadCallLog] permission for
    requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not
    found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidactivecalls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidactivecalls-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllog-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Records by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get
  description: "Returns filtered call log records.\nApp Permission\nReadCallLog\nUser
    Permission\nReadCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadCallLog] permission for
    requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidcalllog-get
  description: "Returns call log records filtered by parameters specified.\nApp Permission\nReadCallLog\nUser
    Permission\nFullCompanyCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCLG-110\nParameter
    [sessionId] is not allowed for usage along with parameter [extensionNumber]\n\n\n400\nCMN-101\nParameter
    [dateFrom] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadCompanyCallLog] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingid-get
  description: "Returns call recording metadata by ID.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to
    extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings Data
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingidcontent-get
  description: "Returns media content of a call recording.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found\n\n\n416\nCMN-107\nRequested
    range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Make RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringout-post
  description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller ID: [+18609411729] is
    not allowed\n\n\n400\nTEL-108\nphoneNumber specified in the from field is empty
    or invalid\n\n\n400\nTEL-109\nphoneNumber specified in the to field is empty or
    invalid\n\n\n403\nBIL-103\nFeature [RingOut] is not available for current account\n\n\n403\nCMN-112\nFeature
    [RingOut] is not available for current extension type\n\n\n403\nCMN-113\nFeature
    [DomesticCalls] is not available for current extension\n\n\n403\nRNG-102\nCaller
    ID should be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber specified
    in the to field: [17176704078] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
    specified in the from field: [17176704078] is in blocked list\n\n\n403\nTEL-107\nCaller
    ID: [+12094441763] is not allowed\n\n\n404\nCMN-102\nResource for parameter [forwardingNumberId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringout-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns the status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n503\nCMN-201\nService Temporary Unavailable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Cancel RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
  description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
    Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n404\nCMN-102\nResource for parameter [ringOutId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Make RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringout-post
  description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller ID: [+14152961727] is
    not allowed\n\n\n400\nTEL-108\nphoneNumber specified in the from field is empty
    or invalid\n\n\n400\nTEL-109\nphoneNumber specified in the to field is empty or
    invalid\n\n\n403\nBIL-103\nFeature [RingOut] is not available for current account\n\n\n403\nCMN-112\nFeature
    [RingOut] is not available for current extension type\n\n\n403\nCMN-113\nFeature
    [DomesticCalls] is not available for current extension\n\n\n403\nCMN-401\nIn order
    to call this API endpoint, application needs to have [RingOut] permission\n\n\n403\nRNG-102\nCaller
    ID should be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber specified
    in the to field: [17176704073] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
    specified in the from field: [17172302150] is in blocked list\n\n\n403\nTEL-107\nCaller
    ID: [+12094441789] is not allowed\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringout-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [RingOut] permission\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Cancel RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
  description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
    Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-get
  description: "Returns the extension answering rules.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadUserAnsweringRules] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-post
  description: "Creates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-101\nParameter [forwarding.rules[].forwardingNumbers[].id]
    are duplicated\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-107\nMore
    than one caller with the same [callerId]\n\n\n400\nAWR-108\nOnly custom rule can
    be created\n\n\n400\nAWR-111\nAt least one condition should be specified\n\n\n400\nAWR-113\nMore
    than one called number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-123\nPreset [131840] can not
    be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId specified for
    greeting type [Voicemail] is not found\n\n\n400\nAWR-125\nCustom greeting presetId
    specified for greeting type [Introductory]. Custom greeting uploading method should
    be used\n\n\n400\nAWR-126\nThe amount of schedule ranges exceeds 1000\n\n\n400\nAWR-136\nRing
    group with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater
    than 0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-149\nOnly user, voicemail or shared
    line group extension can be a voicemail recipient\n\n\n400\nAWR-150\nOnly user,
    voicemail, shared line group extension or current department can be a voicemail
    recipient\n\n\n400\nAWR-152\nVoicemail cannot be turned off for call queue extension\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [name] value is invalid\n\n\n400\nFPN-105\nNumber
    +16196093249 duplicates with company/extension direct number\n\n\n400\nFPN-108\nInternational
    calling is currently disabled\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get
  description: "Returns an answering rule by ID.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nLight\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [showInactiveNumbers] value is invalid\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [answering-rule] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Custom Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
  description: "Updates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt
    least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
    number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After
    Hours schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
    [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
    specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing group
    with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater than
    0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction] value
    is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
    direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditExtensions] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete
  description: "Deletes a custom answering rule by a particular ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nAWR-110\nBusiness
    Hours/After Hours rule cannot be deleted\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [answering-rule]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Settings
  x-api-slug: restapiv1-0accountaccountidcallrecording-get
  description: |-
    Returns call recording settings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecording-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
- name: RingCentral Connect Platform API Explorer - [Beta] Get Call Recording Custom
    Greetings
  x-api-slug: restapiv1-0accountaccountidcallrecordingcustomgreetings-get
  description: |-
    Returns call recording custom greetings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingcustomgreetings-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Edit Call Queue Members
  x-api-slug: restapiv1-0accountaccountiddepartmentbulkassign-post
  description: "[Deprecated] Adds and/or removes multiple call queue members\nApp
    Permission\nEditAccounts\nUser Permission\nUserGroups\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nEXT-401\nExtension
    ID should be present only in one section"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountiddepartmentbulkassign-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queues
  x-api-slug: restapiv1-0accountaccountidcallqueues-get
  description: |-
    Returns call queue group list
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueues-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queue Members
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidmembers-get
  description: |-
    Returns call queue group members.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidmembers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Edit Call Queue Group
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post
  description: "Updates call queue group.\nApp Permission\nEditExtensions\nUser Permission\nGroups\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nEXT-405\nExtension of type [ParkLocation] could not be
    a member of [department}]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Monitoring Groups
  x-api-slug: restapiv1-0accountaccountidcallmonitoringgroups-get
  description: |-
    Returns call monitoring groups that can be filtered by some extension.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallmonitoringgroups-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Monitoring Group Members
  x-api-slug: restapiv1-0accountaccountidcallmonitoringgroupsgroupidmembers-get
  description: |-
    Returns call monitoring group members.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallmonitoringgroupsgroupidmembers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllog-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Records by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get
  description: "Returns filtered call log records.\nApp Permission\nReadCallLog\nUser
    Permission\nReadCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadCallLog] permission for
    requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidcalllog-get
  description: "Returns call log records filtered by parameters specified.\nApp Permission\nReadCallLog\nUser
    Permission\nFullCompanyCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCLG-110\nParameter
    [sessionId] is not allowed for usage along with parameter [extensionNumber]\n\n\n400\nCMN-101\nParameter
    [dateFrom] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadCompanyCallLog] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingid-get
  description: "Returns call recording metadata by ID.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to
    extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings Data
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingidcontent-get
  description: "Returns media content of a call recording.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found\n\n\n416\nCMN-107\nRequested
    range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Make RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringout-post
  description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller ID: [+18609411729] is
    not allowed\n\n\n400\nTEL-108\nphoneNumber specified in the from field is empty
    or invalid\n\n\n400\nTEL-109\nphoneNumber specified in the to field is empty or
    invalid\n\n\n403\nBIL-103\nFeature [RingOut] is not available for current account\n\n\n403\nCMN-112\nFeature
    [RingOut] is not available for current extension type\n\n\n403\nCMN-113\nFeature
    [DomesticCalls] is not available for current extension\n\n\n403\nRNG-102\nCaller
    ID should be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber specified
    in the to field: [17176704078] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
    specified in the from field: [17176704078] is in blocked list\n\n\n403\nTEL-107\nCaller
    ID: [+12094441763] is not allowed\n\n\n404\nCMN-102\nResource for parameter [forwardingNumberId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringout-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns the status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n503\nCMN-201\nService Temporary Unavailable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Cancel RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
  description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
    Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n404\nCMN-102\nResource for parameter [ringOutId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Make RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringout-post
  description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller ID: [+14152961727] is
    not allowed\n\n\n400\nTEL-108\nphoneNumber specified in the from field is empty
    or invalid\n\n\n400\nTEL-109\nphoneNumber specified in the to field is empty or
    invalid\n\n\n403\nBIL-103\nFeature [RingOut] is not available for current account\n\n\n403\nCMN-112\nFeature
    [RingOut] is not available for current extension type\n\n\n403\nCMN-113\nFeature
    [DomesticCalls] is not available for current extension\n\n\n403\nCMN-401\nIn order
    to call this API endpoint, application needs to have [RingOut] permission\n\n\n403\nRNG-102\nCaller
    ID should be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber specified
    in the to field: [17176704073] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
    specified in the from field: [17172302150] is in blocked list\n\n\n403\nTEL-107\nCaller
    ID: [+12094441789] is not allowed\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringout-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [RingOut] permission\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Cancel RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
  description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
    Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-get
  description: "Returns the extension answering rules.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadUserAnsweringRules] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-post
  description: "Creates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-101\nParameter [forwarding.rules[].forwardingNumbers[].id]
    are duplicated\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-107\nMore
    than one caller with the same [callerId]\n\n\n400\nAWR-108\nOnly custom rule can
    be created\n\n\n400\nAWR-111\nAt least one condition should be specified\n\n\n400\nAWR-113\nMore
    than one called number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-123\nPreset [131840] can not
    be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId specified for
    greeting type [Voicemail] is not found\n\n\n400\nAWR-125\nCustom greeting presetId
    specified for greeting type [Introductory]. Custom greeting uploading method should
    be used\n\n\n400\nAWR-126\nThe amount of schedule ranges exceeds 1000\n\n\n400\nAWR-136\nRing
    group with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater
    than 0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-149\nOnly user, voicemail or shared
    line group extension can be a voicemail recipient\n\n\n400\nAWR-150\nOnly user,
    voicemail, shared line group extension or current department can be a voicemail
    recipient\n\n\n400\nAWR-152\nVoicemail cannot be turned off for call queue extension\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [name] value is invalid\n\n\n400\nFPN-105\nNumber
    +16196093249 duplicates with company/extension direct number\n\n\n400\nFPN-108\nInternational
    calling is currently disabled\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get
  description: "Returns an answering rule by ID.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nLight\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [showInactiveNumbers] value is invalid\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [answering-rule] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Custom Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
  description: "Updates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt
    least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
    number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After
    Hours schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
    [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
    specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing group
    with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater than
    0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction] value
    is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
    direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditExtensions] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete
  description: "Deletes a custom answering rule by a particular ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nAWR-110\nBusiness
    Hours/After Hours rule cannot be deleted\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [answering-rule]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Settings
  x-api-slug: restapiv1-0accountaccountidcallrecording-get
  description: |-
    Returns call recording settings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecording-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
- name: RingCentral Connect Platform API Explorer - [Beta] Get Call Recording Custom
    Greetings
  x-api-slug: restapiv1-0accountaccountidcallrecordingcustomgreetings-get
  description: |-
    Returns call recording custom greetings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingcustomgreetings-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Edit Call Queue Members
  x-api-slug: restapiv1-0accountaccountiddepartmentbulkassign-post
  description: "[Deprecated] Adds and/or removes multiple call queue members\nApp
    Permission\nEditAccounts\nUser Permission\nUserGroups\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nEXT-401\nExtension
    ID should be present only in one section"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountiddepartmentbulkassign-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queues
  x-api-slug: restapiv1-0accountaccountidcallqueues-get
  description: |-
    Returns call queue group list
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueues-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queue Members
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidmembers-get
  description: |-
    Returns call queue group members.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidmembers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Edit Call Queue Group
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post
  description: "Updates call queue group.\nApp Permission\nEditExtensions\nUser Permission\nGroups\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nEXT-405\nExtension of type [ParkLocation] could not be
    a member of [department}]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Monitoring Groups
  x-api-slug: restapiv1-0accountaccountidcallmonitoringgroups-get
  description: |-
    Returns call monitoring groups that can be filtered by some extension.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallmonitoringgroups-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Monitoring Group Members
  x-api-slug: restapiv1-0accountaccountidcallmonitoringgroupsgroupidmembers-get
  description: |-
    Returns call monitoring group members.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallmonitoringgroupsgroupidmembers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Monitoring Group Members
  x-api-slug: restapiv1-0accountaccountidcallmonitoringgroupsgroupidmembers-get
  description: |-
    Returns call monitoring group members.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallmonitoringgroupsgroupidmembers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Monitoring Groups
  x-api-slug: restapiv1-0accountaccountidcallmonitoringgroups-get
  description: |-
    Returns call monitoring groups that can be filtered by some extension.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallmonitoringgroups-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Monitoring Groups
  x-api-slug: restapiv1-0accountaccountidcallmonitoringgroups-get
  description: |-
    Returns call monitoring groups that can be filtered by some extension.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallmonitoringgroups-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Edit Call Queue Group
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post
  description: "Updates call queue group.\nApp Permission\nEditExtensions\nUser Permission\nGroups\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nEXT-405\nExtension of type [ParkLocation] could not be
    a member of [department}]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Edit Call Queue Group
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post
  description: "Updates call queue group.\nApp Permission\nEditExtensions\nUser Permission\nGroups\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nEXT-405\nExtension of type [ParkLocation] could not be
    a member of [department}]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Edit Call Queue Group
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post
  description: "Updates call queue group.\nApp Permission\nEditExtensions\nUser Permission\nGroups\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nEXT-405\nExtension of type [ParkLocation] could not be
    a member of [department}]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidbulkassign-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queue Members
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidmembers-get
  description: |-
    Returns call queue group members.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidmembers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queue Members
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidmembers-get
  description: |-
    Returns call queue group members.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidmembers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queue Members
  x-api-slug: restapiv1-0accountaccountidcallqueuesgroupidmembers-get
  description: |-
    Returns call queue group members.
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueuesgroupidmembers-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queues
  x-api-slug: restapiv1-0accountaccountidcallqueues-get
  description: |-
    Returns call queue group list
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueues-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Queues
  x-api-slug: restapiv1-0accountaccountidcallqueues-get
  description: |-
    Returns call queue group list
    App Permission
    ReadAccounts
    User Permission
    ReadExtensions
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallqueues-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Edit Call Queue Members
  x-api-slug: restapiv1-0accountaccountiddepartmentbulkassign-post
  description: "[Deprecated] Adds and/or removes multiple call queue members\nApp
    Permission\nEditAccounts\nUser Permission\nUserGroups\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nEXT-401\nExtension
    ID should be present only in one section"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountiddepartmentbulkassign-post-openapi.md
- name: RingCentral Connect Platform API Explorer - [Beta] Get Call Recording Custom
    Greetings
  x-api-slug: restapiv1-0accountaccountidcallrecordingcustomgreetings-get
  description: |-
    Returns call recording custom greetings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingcustomgreetings-get-openapi.md
- name: RingCentral Connect Platform API Explorer - [Beta] Get Call Recording Custom
    Greetings
  x-api-slug: restapiv1-0accountaccountidcallrecordingcustomgreetings-get
  description: |-
    Returns call recording custom greetings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingcustomgreetings-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Settings
  x-api-slug: restapiv1-0accountaccountidcallrecording-get
  description: |-
    Returns call recording settings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecording-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Settings
  x-api-slug: restapiv1-0accountaccountidcallrecording-get
  description: |-
    Returns call recording settings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecording-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete
  description: "Deletes a custom answering rule by a particular ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nAWR-110\nBusiness
    Hours/After Hours rule cannot be deleted\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [answering-rule]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete
  description: "Deletes a custom answering rule by a particular ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nAWR-110\nBusiness
    Hours/After Hours rule cannot be deleted\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [answering-rule]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Custom Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
  description: "Updates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt
    least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
    number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After
    Hours schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
    [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
    specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing group
    with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater than
    0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction] value
    is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
    direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditExtensions] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Custom Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
  description: "Updates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt
    least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
    number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After
    Hours schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
    [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
    specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing group
    with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater than
    0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction] value
    is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
    direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditExtensions] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get
  description: "Returns an answering rule by ID.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nLight\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [showInactiveNumbers] value is invalid\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [answering-rule] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-post
  description: "Creates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-101\nParameter [forwarding.rules[].forwardingNumbers[].id]
    are duplicated\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-107\nMore
    than one caller with the same [callerId]\n\n\n400\nAWR-108\nOnly custom rule can
    be created\n\n\n400\nAWR-111\nAt least one condition should be specified\n\n\n400\nAWR-113\nMore
    than one called number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-123\nPreset [131840] can not
    be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId specified for
    greeting type [Voicemail] is not found\n\n\n400\nAWR-125\nCustom greeting presetId
    specified for greeting type [Introductory]. Custom greeting uploading method should
    be used\n\n\n400\nAWR-126\nThe amount of schedule ranges exceeds 1000\n\n\n400\nAWR-136\nRing
    group with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater
    than 0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-149\nOnly user, voicemail or shared
    line group extension can be a voicemail recipient\n\n\n400\nAWR-150\nOnly user,
    voicemail, shared line group extension or current department can be a voicemail
    recipient\n\n\n400\nAWR-152\nVoicemail cannot be turned off for call queue extension\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [name] value is invalid\n\n\n400\nFPN-105\nNumber
    +16196093249 duplicates with company/extension direct number\n\n\n400\nFPN-108\nInternational
    calling is currently disabled\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-post
  description: "Creates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-101\nParameter [forwarding.rules[].forwardingNumbers[].id]
    are duplicated\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-107\nMore
    than one caller with the same [callerId]\n\n\n400\nAWR-108\nOnly custom rule can
    be created\n\n\n400\nAWR-111\nAt least one condition should be specified\n\n\n400\nAWR-113\nMore
    than one called number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-123\nPreset [131840] can not
    be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId specified for
    greeting type [Voicemail] is not found\n\n\n400\nAWR-125\nCustom greeting presetId
    specified for greeting type [Introductory]. Custom greeting uploading method should
    be used\n\n\n400\nAWR-126\nThe amount of schedule ranges exceeds 1000\n\n\n400\nAWR-136\nRing
    group with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater
    than 0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-149\nOnly user, voicemail or shared
    line group extension can be a voicemail recipient\n\n\n400\nAWR-150\nOnly user,
    voicemail, shared line group extension or current department can be a voicemail
    recipient\n\n\n400\nAWR-152\nVoicemail cannot be turned off for call queue extension\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [name] value is invalid\n\n\n400\nFPN-105\nNumber
    +16196093249 duplicates with company/extension direct number\n\n\n400\nFPN-108\nInternational
    calling is currently disabled\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-get
  description: "Returns the extension answering rules.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadUserAnsweringRules] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-get
  description: "Returns the extension answering rules.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadUserAnsweringRules] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Cancel RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
  description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
    Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Cancel RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
  description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
    Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n404\nCMN-102\nResource for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [RingOut] permission\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [RingOut] permission\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [RingOut] permission\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Make RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringout-post
  description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller ID: [+14152961727] is
    not allowed\n\n\n400\nTEL-108\nphoneNumber specified in the from field is empty
    or invalid\n\n\n400\nTEL-109\nphoneNumber specified in the to field is empty or
    invalid\n\n\n403\nBIL-103\nFeature [RingOut] is not available for current account\n\n\n403\nCMN-112\nFeature
    [RingOut] is not available for current extension type\n\n\n403\nCMN-113\nFeature
    [DomesticCalls] is not available for current extension\n\n\n403\nCMN-401\nIn order
    to call this API endpoint, application needs to have [RingOut] permission\n\n\n403\nRNG-102\nCaller
    ID should be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber specified
    in the to field: [17176704073] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
    specified in the from field: [17172302150] is in blocked list\n\n\n403\nTEL-107\nCaller
    ID: [+12094441789] is not allowed\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringout-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Cancel RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
  description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
    Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n404\nCMN-102\nResource for parameter [ringOutId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Cancel RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete
  description: "Cancels a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan
    Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n404\nCMN-102\nResource for parameter [ringOutId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns the status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n503\nCMN-201\nService Temporary Unavailable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns the status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n503\nCMN-201\nService Temporary Unavailable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Status of RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringoutringoutid-get
  description: "Returns the status of a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n503\nCMN-201\nService Temporary Unavailable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringoutringoutid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Make RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringout-post
  description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller ID: [+18609411729] is
    not allowed\n\n\n400\nTEL-108\nphoneNumber specified in the from field is empty
    or invalid\n\n\n400\nTEL-109\nphoneNumber specified in the to field is empty or
    invalid\n\n\n403\nBIL-103\nFeature [RingOut] is not available for current account\n\n\n403\nCMN-112\nFeature
    [RingOut] is not available for current extension type\n\n\n403\nCMN-113\nFeature
    [DomesticCalls] is not available for current extension\n\n\n403\nRNG-102\nCaller
    ID should be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber specified
    in the to field: [17176704078] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
    specified in the from field: [17176704078] is in blocked list\n\n\n403\nTEL-107\nCaller
    ID: [+12094441763] is not allowed\n\n\n404\nCMN-102\nResource for parameter [forwardingNumberId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringout-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Make RingOut Call
  x-api-slug: restapiv1-0accountaccountidextensionextensionidringout-post
  description: "Makes a 2-leg RingOut call.\nApp Permission\nRingOut\nUsage Plan Group\nHeavy\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [phoneNumber] value is invalid\n\n\n400\nTEL-107\nCaller ID: [+18609411729] is
    not allowed\n\n\n400\nTEL-108\nphoneNumber specified in the from field is empty
    or invalid\n\n\n400\nTEL-109\nphoneNumber specified in the to field is empty or
    invalid\n\n\n403\nBIL-103\nFeature [RingOut] is not available for current account\n\n\n403\nCMN-112\nFeature
    [RingOut] is not available for current extension type\n\n\n403\nCMN-113\nFeature
    [DomesticCalls] is not available for current extension\n\n\n403\nRNG-102\nCaller
    ID should be one of company direct numbers\n\n\n403\nTEL-101\nphoneNumber specified
    in the to field: [17176704078] is in blocked list\n\n\n403\nTEL-102\nphoneNumber
    specified in the from field: [17176704078] is in blocked list\n\n\n403\nTEL-107\nCaller
    ID: [+12094441763] is not allowed\n\n\n404\nCMN-102\nResource for parameter [forwardingNumberId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidringout-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings Data
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingidcontent-get
  description: "Returns media content of a call recording.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found\n\n\n416\nCMN-107\nRequested
    range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings Data
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingidcontent-get
  description: "Returns media content of a call recording.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found\n\n\n416\nCMN-107\nRequested
    range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings Data
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingidcontent-get
  description: "Returns media content of a call recording.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
    Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
    access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found\n\n\n416\nCMN-107\nRequested
    range not satisfiable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingidcontent-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingid-get
  description: "Returns call recording metadata by ID.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to
    extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingid-get
  description: "Returns call recording metadata by ID.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to
    extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recordings
  x-api-slug: restapiv1-0accountaccountidrecordingrecordingid-get
  description: "Returns call recording metadata by ID.\nApp Permission\nReadCallRecording\nUser
    Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to
    extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadCallRecording]
    permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidrecordingrecordingid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidcalllog-get
  description: "Returns call log records filtered by parameters specified.\nApp Permission\nReadCallLog\nUser
    Permission\nFullCompanyCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCLG-110\nParameter
    [sessionId] is not allowed for usage along with parameter [extensionNumber]\n\n\n400\nCMN-101\nParameter
    [dateFrom] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadCompanyCallLog] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidcalllog-get
  description: "Returns call log records filtered by parameters specified.\nApp Permission\nReadCallLog\nUser
    Permission\nFullCompanyCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCLG-110\nParameter
    [sessionId] is not allowed for usage along with parameter [extensionNumber]\n\n\n400\nCMN-101\nParameter
    [dateFrom] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadCompanyCallLog] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidcalllog-get
  description: "Returns call log records filtered by parameters specified.\nApp Permission\nReadCallLog\nUser
    Permission\nFullCompanyCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCLG-110\nParameter
    [sessionId] is not allowed for usage along with parameter [extensionNumber]\n\n\n400\nCMN-101\nParameter
    [dateFrom] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadCompanyCallLog] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Records by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get
  description: "Returns filtered call log records.\nApp Permission\nReadCallLog\nUser
    Permission\nReadCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadCallLog] permission for
    requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Records by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get
  description: "Returns filtered call log records.\nApp Permission\nReadCallLog\nUser
    Permission\nReadCallLog\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [ReadCallLog] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadCallLog] permission for
    requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId] is
    not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllogcallrecordid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllog-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllog-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Log Records by Filter
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcalllog-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcalllog-get-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---