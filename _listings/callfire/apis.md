---
name: CallFire
x-slug: callfire
description: Grow your business with virtual phone numbers, IVR, voice broadcasting,
  mass text messaging services and power dialing. Try CallFire for FREE!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
x-kinRank: "9"
x-alexaRank: "129466"
tags: Calls
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/apis.md
specificationVersion: "0.14"
apis:
- name: CallFire - Find calls
  x-api-slug: calls-get
  description: To search for all calls sent or received by the user. Use "id=0" for
    the campaignId parameter to query for all calls sent through the POST /calls API.
    See [call states and results](https://developers.callfire.com/results-responses-errors.html)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/calls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/calls-get-openapi.md
- name: CallFire - Send calls
  x-api-slug: calls-post
  description: Use the /calls API to send individual calls quickly. A verified Caller
    ID and sufficient credits are required to make a call. CallRecipient represents
    a single recipient identified by phone number or contact id in CallFire system.
    You can attach user-defined attributes to a Call action via CallRecipient.attributes
    property, attributes are available in Call action response
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/calls-post-openapi.md
- name: CallFire - Find call broadcasts
  x-api-slug: callsbroadcasts-get
  description: Searches for all voice broadcasts created by user. Can query on label,
    name, and the current running status of the campaign. Returns a paged list of
    voice broadcasts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcasts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcasts-get-openapi.md
- name: CallFire - Create a call broadcast
  x-api-slug: callsbroadcasts-post
  description: Creates a call broadcast campaign using the Call Broadcast API. Send
    a CallBroadcast in the message body to add details in a voice broadcast campaign.
    The campaign can be created without contacts and bare minimum configuration, but
    contacts will have to be added further on to use the campaign
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcasts-post-openapi.md
- name: CallFire - Find a specific call broadcast
  x-api-slug: callsbroadcastsid-get
  description: Returns a single CallBroadcast instance for a given call broadcast
    campaign id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsid-get-openapi.md
- name: CallFire - Update a call broadcast
  x-api-slug: callsbroadcastsid-put
  description: This operation lets the user modify the configuration of a voice broadcast
    campaign after call broadcast campaign is created. See CallBroadcast for more
    information on what can/can't be updated on this API
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsid-put-openapi.md
- name: CallFire - Archive voice broadcast
  x-api-slug: callsbroadcastsidarchive-post
  description: Archives a voice broadcast (voice broadcast will be hidden in search
    results)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidarchive-post-openapi.md
- name: CallFire - Find batches in a call broadcast
  x-api-slug: callsbroadcastsidbatches-get
  description: This endpoint will enable the user to page through all of the batches
    for a particular voice broadcast campaign
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidbatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidbatches-get-openapi.md
- name: CallFire - Add batches to a call broadcast
  x-api-slug: callsbroadcastsidbatches-post
  description: The 'add batch' API allows user to add additional batches to an already
    created voice broadcast campaign. The added batch will go through the CallFire
    validation process, unlike in the recipients version of this API. That is why
    you can use the scrubDuplicates flag to remove duplicates from your batch. Batches
    may be added as a contact list id, a list of contact ids, or a list of numbers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidbatches-post-openapi.md
- name: CallFire - Find calls in a call broadcast
  x-api-slug: callsbroadcastsidcalls-get
  description: This endpoint will enable the user to page through all calls for a
    particular call broadcast campaign
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidcalls-get-openapi.md
- name: CallFire - Add recipients to a call broadcast
  x-api-slug: callsbroadcastsidrecipients-post
  description: Use this API to add the recipients to an existing voice broadcast.
    Post a list of Recipient objects to be added to the voice broadcast campaign.
    These contacts will not go through validation process, and will be acted upon
    as they are added. Recipients may be added as a list of contact ids, or list of
    numbers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidrecipients-post-openapi.md
- name: CallFire - Start voice broadcast
  x-api-slug: callsbroadcastsidstart-post
  description: Start a voice broadcast
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidstart-post-openapi.md
- name: CallFire - Get statistics on call broadcast
  x-api-slug: callsbroadcastsidstats-get
  description: Returns broadcast statistics like total number of sent/received actions,
    total cost, number of remaining outbound actions, error count, etc
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidstats-get-openapi.md
- name: CallFire - Stop voice broadcast
  x-api-slug: callsbroadcastsidstop-post
  description: Stop a voice broadcast
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsbroadcastsidstop-post-openapi.md
- name: CallFire - Get call recording by id
  x-api-slug: callsrecordingsid-get
  description: Returns metadata of recording of a particular call. Metadata contains
    a link to a MP3 recording
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsrecordingsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsrecordingsid-get-openapi.md
- name: CallFire - Get call recording in mp3 format
  x-api-slug: callsrecordingsid-mp3-get
  description: Returns an MP3 recording of particular call, response contains binary
    data, content type is 'audio/mpeg'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsrecordingsid-mp3-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsrecordingsid-mp3-get-openapi.md
- name: CallFire - Find a specific call
  x-api-slug: callsid-get
  description: Returns a single Call instance for a given call id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsid-get-openapi.md
- name: CallFire - Get call recordings for a call
  x-api-slug: callsidrecordings-get
  description: Returns a list of recordings metadata of particular call. Metadata
    contains link to a MP3 recording
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsidrecordings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsidrecordings-get-openapi.md
- name: CallFire - Get call recording by name
  x-api-slug: callsidrecordingsname-get
  description: Returns recording metadata of particular call. Metadata contains link
    to a MP3 recording
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsidrecordingsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsidrecordingsname-get-openapi.md
- name: CallFire - Get call mp3 recording by name
  x-api-slug: callsidrecordingsname-mp3-get
  description: Returns a MP3 recording of a particular call, response contains binary
    data, content type is 'audio/mpeg'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsidrecordingsname-mp3-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/callsidrecordingsname-mp3-get-openapi.md
- name: CallFire - Add sound via call
  x-api-slug: campaignssoundscalls-post
  description: Use this API to create a sound via a phone call. Provide the required
    phone number in the CallCreateSound object inside the request, and user will receive
    a call shortly after with instructions on how to record a sound over the phone.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calls/master/_listings/callfire/campaignssoundscalls-post-openapi.md
x-common:
- type: x--net-sdk
  url: https://github.com/CallFire/CallFire-CSharp-SDK
- type: x-account-billing
  url: https://answers.callfire.com/hc/en-us/sections/200166268-Billing
- type: x-account-settings
  url: https://answers.callfire.com/hc/en-us/sections/200187056-Account-Settings
- type: x-api-gallery
  url: http://bureau.of.justice.statistics.api.gallery.streamdata.io
- type: x-api-stack
  url: http://callfire.stack.network
- type: x-authentication
  url: https://www.callfire.com/api-documentation/how-do-i-enable-api-on-my-account
- type: x-blog
  url: https://www.callfire.com/blog
- type: x-blog-rss
  url: https://www.callfire.com/blog/feed
- type: x-twitter
  url: https://twitter.com/CallFire
- type: x-case-studies
  url: https://www.callfire.com/case-studies
- type: x-compliance
  url: https://www.callfire.com/legal/compliance
- type: x-contact-form
  url: https://www.callfire.com/contact
- type: x-crunchbase
  url: https://www.crunchbase.com/organization/callfire
- type: x-crunchbase
  url: https://crunchbase.com/organization/callfire
- type: x-developer
  url: https://www.callfire.com/api-documentation
- type: x-documentation
  url: https://www.callfire.com/api-documentation/rest/version/1.1
- type: x-drupal-plugin
  url: https://github.com/CallFire/CallFire-Drupal-Integration
- type: x-email
  url: answers@callfire.com
- type: x-email
  url: support@callfire.com
- type: x-facebook
  url: https://www.facebook.com/callfire
- type: x-faq
  url: https://answers.callfire.com/hc/en-us/sections/200193833-FAQs
- type: x-getting-started
  url: https://www.callfire.com/help/docs/getting-started
- type: x-github
  url: https://github.com/callfire
- type: x-glossary
  url: https://www.callfire.com/help/glossary/communications
- type: x-google-plus
  url: https://plus.google.com/100142045997033051154
- type: x-messages
  url: https://www.callfire.com/ui/number/messages?6
- type: x-partners
  url: https://www.callfire.com/partners
- type: x-phone
  url: 1.877.897.3473
- type: x-php-sdk
  url: https://github.com/CallFire/CallFire-PHP-SDK
- type: x-pricing
  url: https://www.callfire.com/pricing
- type: x-privacy
  url: https://www.callfire.com/legal/privacy
- type: x-selfservice-registration
  url: https://www.callfire.com/ui/register?1
- type: x-terms-of-service
  url: https://www.callfire.com/legal/terms
- type: x-tickets
  url: https://answers.callfire.com/hc/en-us/requests/new
- type: x-tour
  url: javascript:;
- type: x-videos
  url: https://answers.callfire.com/hc/en-us/articles/200849247-Videos
- type: x-webinars
  url: https://answers.callfire.com/hc/en-us/articles/202174798-Webinars
- type: x-website
  url: http://www.callfire.com
- type: x-wordpress-plugin
  url: https://github.com/CallFire/CallFire-WordPress-Integration
- type: x-youtube
  url: https://www.youtube.com/user/CallFireTelephony
- type: x-zapier
  url: https://zapier.com/zapbook/callfire/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---