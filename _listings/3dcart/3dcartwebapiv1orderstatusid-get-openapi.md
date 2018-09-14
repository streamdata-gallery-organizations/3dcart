---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get an OrderStatus
  version: 1.0.0
  description: Get an orderstatus.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/OrderStatus/{id}:
    get:
      summary: Get an OrderStatus
      description: Get an orderstatus.
      operationId: OrderStatus_GetOrderStatus
      x-api-path-slug: 3dcartwebapiv1orderstatusid-get
      parameters:
      - in: path
        name: id
        description: OrderStatus ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - OrderStatus
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