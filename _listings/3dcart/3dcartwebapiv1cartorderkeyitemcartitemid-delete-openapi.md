---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Deletes a CartItem in the system
  version: 1.0.0
  description: Deletes a cartitem in the system.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Cart/{orderkey}/Item/{cartitemid}:
    delete:
      summary: Deletes a CartItem in the system
      description: Deletes a cartitem in the system.
      operationId: Carts_Delete
      x-api-path-slug: 3dcartwebapiv1cartorderkeyitemcartitemid-delete
      parameters:
      - in: path
        name: cartitemid
        description: The unique index ID of an Item
      - in: path
        name: orderkey
        description: Order Key
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
      - S
      - CartItem
      - In
      - System
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