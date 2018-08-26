---
name: Lisk
x-slug: lisk
description: Lisk makes it easy for developers to build and deploy blockchain applications
  in JavaScript. Join the leading platform for world-changing dapps.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
x-kinRank: "7"
x-alexaRank: "145661"
tags: Lisk
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/apis.md
specificationVersion: "0.14"
apis:
- name: Lisk API Documentation - Requests account data
  x-api-slug: accounts-get
  description: Search for matching accounts in the system.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
  humanURL: https://lisk.io
  baseURL: https:////api
  tags: Technology, SaaS, Enterprise, Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/accounts-get-openapi.md
- name: Lisk API Documentation - Requests multisignature groups data
  x-api-slug: accountsaddressmultisignature-groups-get
  description: Searches for the specified account in the system and responds with
    a list of the multisignature groups that this account is member of.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
  humanURL: https://lisk.io
  baseURL: https:////api
  tags: Technology, SaaS, Enterprise, Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/accountsaddressmultisignature-groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/accountsaddressmultisignature-groups-get-openapi.md
- name: Lisk API Documentation - Requests multisignature membership data
  x-api-slug: accountsaddressmultisignature-memberships-get
  description: Searches for the specified multisignature group and responds with a
    list of all members of this particular multisignature group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
  humanURL: https://lisk.io
  baseURL: https:////api
  tags: Technology, SaaS, Enterprise, Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/accountsaddressmultisignature-memberships-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/accountsaddressmultisignature-memberships-get-openapi.md
- name: Lisk API Documentation - Requests dapps data
  x-api-slug: dapps-get
  description: Search for a specified dapp in the system.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
  humanURL: https://lisk.io
  baseURL: https:////api
  tags: Technology, SaaS, Enterprise, Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/dapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/dapps-get-openapi.md
- name: Lisk API Documentation - Requests peers data
  x-api-slug: peers-get
  description: Search for specified peers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
  humanURL: https://lisk.io
  baseURL: https:////api
  tags: Technology, SaaS, Enterprise, Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/peers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/peers-get-openapi.md
- name: Lisk API Documentation - Requests constants data
  x-api-slug: nodeconstants-get
  description: Returns all current constants data on the system, e.g. Lisk epoch time
    and version.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
  humanURL: https://lisk.io
  baseURL: https:////api
  tags: Technology, SaaS, Enterprise, Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/nodeconstants-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/nodeconstants-get-openapi.md
- name: Lisk API Documentation - Requests status data
  x-api-slug: nodestatus-get
  description: Returns all current status data of the node, e.g. height and broadhash.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
  humanURL: https://lisk.io
  baseURL: https:////api
  tags: Technology, SaaS, Enterprise, Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/nodestatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/nodestatus-get-openapi.md
- name: Lisk API Documentation - Requests forging status of a delegate
  x-api-slug: nodestatusforging-get
  description: |-
    *Attention! This is a **private endpoint only authorized to whitelisted IPs.**
    To edit the whitelist, please edit the `forging.access.whitelist` section in `config.json`*<br>
    Responds with the forging status of a delegate on a node.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26631-lisk.jpg
  humanURL: https://lisk.io
  baseURL: https:////api
  tags: Technology, SaaS, Enterprise, Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/nodestatusforging-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lisk/master/_listings/lisk/nodestatusforging-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://linkedin.api.gallery.streamdata.io
- type: x-crunchbase
  url: https://crunchbase.com/organization/lisk
- type: x-email
  url: support@lisk.io
- type: x-email
  url: dataprotection@lisk.io
- type: x-email
  url: help@lisk.io
- type: x-email
  url: business@lisk.io
- type: x-email
  url: events@lisk.io
- type: x-twitter
  url: https://twitter.com/LiskHQ
- type: x-website
  url: https://lisk.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---