---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Updates a specific feature from a specific Product
  version: 1.0.0
  description: Updates a specific feature from a specific product.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Products/{catalogid}/Features/{featureid}:
    put:
      summary: Updates a specific feature from a specific Product
      description: Updates a specific feature from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidfeaturesfeatureid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: feature
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: featureid
        description: FeatureID
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
      - Specific
      - Feature
      - From
      - Specific
      - Product
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