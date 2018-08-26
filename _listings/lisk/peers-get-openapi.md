---
swagger: "2.0"
x-collection-name: Lisk
x-complete: 0
info:
  title: Lisk Requests peers data
  description: Search for specified peers.
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts:
    get:
      summary: Requests account data
      description: Search for matching accounts in the system.
      operationId: getAccounts
      x-api-path-slug: accounts-get
      parameters:
      - in: query
        name: address
        description: Address of an account
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: offset
        description: Offset value for results
      - in: query
        name: publicKey
        description: Public key to query
      - in: query
        name: secondPublicKey
        description: Second public key to query
      - in: query
        name: sort
        description: Fields to sort results by
      - in: query
        name: username
        description: Delegate username to query
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Account
      - Data
  /accounts/{address}/multisignature_groups:
    get:
      summary: Requests multisignature groups data
      description: Searches for the specified account in the system and responds with
        a list of the multisignature groups that this account is member of.
      operationId: getMultisignatureGroups
      x-api-path-slug: accountsaddressmultisignature-groups-get
      parameters:
      - in: path
        name: address
        description: Lisk address of an account
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Multisignature
      - Groups
      - Data
  /accounts/{address}/multisignature_memberships:
    get:
      summary: Requests multisignature membership data
      description: Searches for the specified multisignature group and responds with
        a list of all members of this particular multisignature group.
      operationId: getMultisignatureMemberships
      x-api-path-slug: accountsaddressmultisignature-memberships-get
      parameters:
      - in: path
        name: address
        description: Lisk address of a multisignature account
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Multisignature
      - Membership
      - Data
  /dapps:
    get:
      summary: Requests dapps data
      description: Search for a specified dapp in the system.
      operationId: getDapps
      x-api-path-slug: dapps-get
      parameters:
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: name
        description: Name to query - Fuzzy search
      - in: query
        name: offset
        description: Offset value for results
      - in: query
        name: sort
        description: Fields to sort results by
      - in: query
        name: transactionId
        description: Dapp registration transaction ID
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Dapps
      - Data
  /peers:
    get:
      summary: Requests peers data
      description: Search for specified peers.
      operationId: getPeers
      x-api-path-slug: peers-get
      parameters:
      - in: query
        name: broadhash
        description: Broadhash of the network
      - in: query
        name: height
        description: Current height of the network
      - in: query
        name: httpPort
        description: Http port of the node or delegate
      - in: query
        name: ip
        description: IP of the node or delegate
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: offset
        description: Offset value for results
      - in: query
        name: os
        description: OS of the node
      - in: query
        name: sort
        description: Fields to sort results by
      - in: query
        name: state
        description: Current state of the network
      - in: query
        name: version
        description: Lisk version of the node
      - in: query
        name: wsPort
        description: Web socket port for the node or delegate
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Peers
      - Data
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