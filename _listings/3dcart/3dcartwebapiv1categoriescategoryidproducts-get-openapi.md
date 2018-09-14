---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all products from a specific category
  version: 1.0.0
  description: Get all products from a specific category.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Categories/{categoryid}/Products:
    get:
      summary: Get all products from a specific category
      description: Get all products from a specific category.
      operationId: Products_GetAllProductsFromCategory
      x-api-path-slug: 3dcartwebapiv1categoriescategoryidproducts-get
      parameters:
      - in: path
        name: categoryid
        description: ID of the category
      - in: query
        name: categoryspecial
        description: Category Special Flag
      - in: query
        name: costfrom
        description: Cost of a product
      - in: query
        name: costto
        description: Cost of a product
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: freeshipping
        description: Free Shipping Flag
      - in: query
        name: giftcertificate
        description: Gift Certificate Flag
      - in: query
        name: hide
        description: Hide Flag
      - in: query
        name: homespecial
        description: Home Special Flag
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
        name: name
        description: Name of the product
      - in: query
        name: nonsearchable
        description: Non-Searchable Flag
      - in: query
        name: nontax
        description: Non-Taxable Flag
      - in: query
        name: notforsale
        description: Not For Sale Flag
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: onsale
        description: On Sale Flag
      - in: query
        name: pricefrom
        description: Price of a product
      - in: query
        name: priceto
        description: Price of a product
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: query
        name: rewarddisable
        description: Disable Rewards Flag
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: selfship
        description: Ships by itself Flag
      - in: query
        name: sku
        description: SKU Code of the product
      - in: query
        name: stockfrom
        description: Stock of a product
      - in: query
        name: stockto
        description: Stock of a product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
      - From
      - Specific
      - Category
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