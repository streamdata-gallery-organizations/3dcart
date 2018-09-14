---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart This method is used to update a single product record in the database.
    The {catalogid} parameter specifies which product record to update.
  version: 1.0.0
  description: This method is used to update a single product record in the database.
    the {catalogid} parameter specifies which product record to update..
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Products/{catalogid}:
    put:
      summary: This method is used to update a single product record in the database.
        The {catalogid} parameter specifies which product record to update.
      description: This method is used to update a single product record in the database.
        the {catalogid} parameter specifies which product record to update..
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: product
        description: A Json or XML object containing the new product
        schema:
          $ref: '#/definitions/holder'
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
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Product
      - Record
      - In
      - Database
      - ""
      - Catalogid
      - Parameter
      - Specifies
      - Which
      - Product
      - Record
      - To
      - Update
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