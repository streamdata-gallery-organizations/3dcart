---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Updates a collection of shipments from a specific Order
  version: 1.0.0
  description: Updates a collection of shipments from a specific order.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Orders/{orderid}/Shipments:
    put:
      summary: Updates a collection of shipments from a specific Order
      description: Updates a collection of shipments from a specific order.
      operationId: Orders_Update
      x-api-path-slug: 3dcartwebapiv1ordersorderidshipments-put
      parameters:
      - in: path
        name: orderid
        description: OrderID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: body
        name: shipments
        description: A Json or XML object containing the new shipments
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Shipments
      - From
      - Specific
      - Order
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