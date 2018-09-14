---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all CRMs
  version: 1.0.0
  description: Get all crms.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/CRM:
    get:
      summary: Get all CRMs
      description: Get all crms.
      operationId: CRM_GetAllCRMs
      x-api-path-slug: 3dcartwebapiv1crm-get
      parameters:
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: custid
        description: Customer Id associated with the CRM
      - in: query
        name: customeremail
        description: Customer Email
      - in: query
        name: customeripaddress
        description: Customer Ip Address
      - in: query
        name: customername
        description: Customer Name
      - in: query
        name: customerphone
        description: Customer Phone
      - in: query
        name: departmentid
        description: Department of the CRM
      - in: query
        name: lastactionenddate
        description: Date Last Action (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastactionstartdate
        description: Date Opened (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: openedenddate
        description: Date Last Action (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: openedstartdate
        description: Date Opened (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: orderid
        description: Order Id associated with the CRM
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: query
        name: productid
        description: Product Id associated with the CRM
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: statusid
        description: Status of the CRM
      - in: query
        name: subject
        description: Subject of the CRM
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - CRMs
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