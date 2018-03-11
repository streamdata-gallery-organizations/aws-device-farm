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
  /?Action=StopRun&k=1:
    get:
      summary: ' Stop Run '
      description: Initiates a stop request for the current test run
      operationId: stopRun
      parameters:
      - in: query
        name: arn
        description: Represents the Amazon Resource Name (ARN) of the Device Farm
          run you wish to stop
        type: string
      responses:
        200:
          description: OK
      tags:
      - runs
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