---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Adds a new CRM Message to the system
  version: 1.0.0
  description: Adds a new crm message to the system.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/CRM/{id}/message:
    post:
      summary: Adds a new CRM Message to the system
      description: Adds a new crm message to the system.
      operationId: CRM_PostMessage
      x-api-path-slug: 3dcartwebapiv1crmidmessage-post
      parameters:
      - in: path
        name: id
        description: Id of the CRM where the message will be added
      - in: body
        name: message
        description: A Json or XML object containing the new CRM message
        schema:
          $ref: '#/definitions/holder'
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
      - New
      - CRM
      - Message
      - To
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