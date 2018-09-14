---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get Customers from a Customer Group
  version: 1.0.0
  description: Get customers from a customer group.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/CustomerGroups/{id}/Customers:
    get:
      summary: Get Customers from a Customer Group
      description: Get customers from a customer group.
      operationId: Customers_GetCustomerFromCustomerGroup
      x-api-path-slug: 3dcartwebapiv1customergroupsidcustomers-get
      parameters:
      - in: query
        name: city
        description: City of the Customer
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: country
        description: Country name of the Customer
      - in: query
        name: email
        description: Email of the Customer
      - in: query
        name: firstname
        description: Firstname of the Customer
      - in: path
        name: id
        description: Customer Group ID
      - in: query
        name: lastname
        description: Lastname of the Customer
      - in: query
        name: lastupdateend
        description: End Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastupdatestart
        description: Start Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: phone
        description: Phone of the Customer
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: state
        description: State of the Customer
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Customers
      - From
      - Customer
      - Group
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