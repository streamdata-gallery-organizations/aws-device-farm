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
  /?Action=CreateDevicePool:
    get:
      summary: ' Create Device Pool '
      description: Creates a device pool
      operationId: createDevicePool
      parameters:
      - in: query
        name: description
        description: The device pool's description
        type: string
      - in: query
        name: name
        description: The device pool's name
        type: string
      - in: query
        name: projectArn
        description: The ARN of the project for the device pool
        type: string
      - in: query
        name: rules
        description: The device pool's rules
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