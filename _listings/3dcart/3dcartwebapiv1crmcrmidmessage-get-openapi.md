---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all the messages from a specific CRM
  version: 1.0.0
  description: Get all the messages from a specific crm.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/CRM/{crmid}/message:
    get:
      summary: Get all the messages from a specific CRM
      description: Get all the messages from a specific crm.
      operationId: CRM_GetAllCRMMessages
      x-api-path-slug: 3dcartwebapiv1crmcrmidmessage-get
      parameters:
      - in: path
        name: crmid
        description: CRM ID
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
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Messages
      - From
      - Specific
      - CRM
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