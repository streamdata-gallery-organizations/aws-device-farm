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
  /?Action=CreateUpload&k=1:
    get:
      summary: ' Create Upload '
      description: Uploads an app or test scripts
      operationId: createUpload
      parameters:
      - in: query
        name: contentType
        description: The upload's content type (for example, application/octet-stream)
        type: string
      - in: query
        name: name
        description: The upload's file name
        type: string
      - in: query
        name: projectArn
        description: The ARN of the project for the upload
        type: string
      - in: query
        name: type
        description: The upload's upload type
        type: string
      responses:
        200:
          description: OK
      tags:
      - upload
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