---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart This method is used to update a single distributor record in the database.
    The {distributorid} parameter specifies which distributor to update.
  version: 1.0.0
  description: This method is used to update a single distributor record in the database.
    the {distributorid} parameter specifies which distributor to update..
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Distributors/{distributorid}:
    put:
      summary: This method is used to update a single distributor record in the database.
        The {distributorid} parameter specifies which distributor to update.
      description: This method is used to update a single distributor record in the
        database. the {distributorid} parameter specifies which distributor to update..
      operationId: Distributors_Update
      x-api-path-slug: 3dcartwebapiv1distributorsdistributorid-put
      parameters:
      - in: body
        name: distributor
        description: A Json or XML object containing the new distributor
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: distributorid
        description: Distributor ID
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
      - Distributor
      - Record
      - In
      - Database
      - ""
      - Distributorid
      - Parameter
      - Specifies
      - Which
      - Distributor
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