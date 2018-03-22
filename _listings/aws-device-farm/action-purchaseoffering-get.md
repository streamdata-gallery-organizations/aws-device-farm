---
swagger: "2.0"
info:
  title: AWS Device Farm API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PurchaseOffering:
    get:
      summary: ' Purchase Offering '
      description: Immediately purchases offerings for an AWS account
      operationId: purchaseOffering
      parameters:
      - in: query
        name: offeringId
        description: The ID of the offering
        type: string
      - in: query
        name: quantity
        description: The number of device slots you wish to purchase in an offering
          request
        type: string
      responses:
        200:
          description: OK
      tags:
      - offerings
definitions: []
x-collection-name: AWS Device Farm
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