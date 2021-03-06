---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart This method is used to update a single manufacturer record in the
    database. The {manufacturerid} parameter specifies which manufacturer record to
    update.
  version: 1.0.0
  description: This method is used to update a single manufacturer record in the database.
    the {manufacturerid} parameter specifies which manufacturer record to update..
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Manufacturers/{manufacturerid}:
    put:
      summary: This method is used to update a single manufacturer record in the database.
        The {manufacturerid} parameter specifies which manufacturer record to update.
      description: This method is used to update a single manufacturer record in the
        database. the {manufacturerid} parameter specifies which manufacturer record
        to update..
      operationId: Manufacturer_Update
      x-api-path-slug: 3dcartwebapiv1manufacturersmanufacturerid-put
      parameters:
      - in: body
        name: manufacturer
        description: A Json or XML object containing the new manufacturer
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: manufacturerid
        description: Manufacturer ID
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
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Manufacturer
      - Record
      - In
      - Database
      - ""
      - Manufacturerid
      - Parameter
      - Specifies
      - Which
      - Manufacturer
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