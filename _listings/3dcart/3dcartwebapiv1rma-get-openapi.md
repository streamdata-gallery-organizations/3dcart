---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all RMAs
  version: 1.0.0
  description: Get all rmas.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/RMA:
    get:
      summary: Get all RMAs
      description: Get all rmas.
      operationId: RMA_GetAllRMAs
      x-api-path-slug: 3dcartwebapiv1rma-get
      parameters:
      - in: query
        name: catalogid
        description: CatalogID
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: dateend
        description: Date End (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: datestart
        description: Date Start (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: query
        name: rmamethodid
        description: Method of the RMA
      - in: query
        name: rmareasonid
        description: Reason of the RMA
      - in: query
        name: rmastatusid
        description: Status of the RMA
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: sku
        description: SKU Code of the product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - RMAs
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