---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: '3dcart '
  version: 1.0.0
  description: .
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Orders:
    get:
      summary: ""
      description: .
      operationId: Orders_GetAllOrders
      x-api-path-slug: 3dcartwebapiv1orders-get
      parameters:
      - in: query
        name: billingemail
      - in: query
        name: countonly
      - in: query
        name: dateend
      - in: query
        name: datestart
      - in: query
        name: invoicenumber
      - in: query
        name: invoicenumberend
      - in: query
        name: invoicenumberstart
      - in: query
        name: invoiceprefix
      - in: query
        name: lastupdateend
      - in: query
        name: lastupdatestart
      - in: query
        name: limit
      - in: query
        name: offset
      - in: query
        name: orderstatus
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
      - ""
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