---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all Distributors
  version: 1.0.0
  description: Get all distributors.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Distributors:
    get:
      summary: Get all Distributors
      description: Get all distributors.
      operationId: Distributors_GetAllDistributors
      x-api-path-slug: 3dcartwebapiv1distributors-get
      parameters:
      - in: query
        name: city
        description: City of the Distributor
      - in: query
        name: company
        description: Company Name of the Distributor
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: country
        description: Country name of the Distributor
      - in: query
        name: email
        description: Email of the Distributor
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: phone
        description: Phone of the Distributor
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: state
        description: State of the Distributor
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Distributors
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