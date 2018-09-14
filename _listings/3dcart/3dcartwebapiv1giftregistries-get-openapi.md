---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all GiftRegistries
  version: 1.0.0
  description: Get all giftregistries.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/GiftRegistries:
    get:
      summary: Get all GiftRegistries
      description: Get all giftregistries.
      operationId: GiftRegistries_GetAllGiftRegistries
      x-api-path-slug: 3dcartwebapiv1giftregistries-get
      parameters:
      - in: query
        name: catalogid
        description: Catalog ID
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: dateendcreated
        description: Created Date End (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: dateendevent
        description: Event Date End (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: dateendexpiration
        description: Expiration Date End (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: datestartcreated
        description: Created Date Start (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: datestartevent
        description: Event Date Start (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: datestartexpiration
        description: Expiration Date Start (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
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
      - GiftRegistries
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