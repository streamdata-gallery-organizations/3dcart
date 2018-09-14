---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Deletes a Manufacturer in the system
  version: 1.0.0
  description: Deletes a manufacturer in the system.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Manufacturers/{id}:
    delete:
      summary: Deletes a Manufacturer in the system
      description: Deletes a manufacturer in the system.
      operationId: Manufacturer_Delete
      x-api-path-slug: 3dcartwebapiv1manufacturersid-delete
      parameters:
      - in: path
        name: id
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
      - S
      - Manufacturer
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