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
  /?Action=GetDevicePoolCompatibility:
    get:
      summary: ' Get Device Pool Compatibility '
      description: Gets information about compatibility with a device pool
      operationId: getDevicePoolCompatibility
      parameters:
      - in: query
        name: appArn
        description: The ARN of the app that is associated with the specified device
          pool
        type: string
      - in: query
        name: devicePoolArn
        description: The device pool's ARN
        type: string
      - in: query
        name: testType
        description: The test type for the specified device pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - device pool
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