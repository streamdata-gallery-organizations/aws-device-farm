---
swagger: "2.0"
x-collection-name: AWS Device Farm
x-complete: 0
info:
  title: AWS Device Farm API Delete Device Pool
  version: 1.0.0
  description: Deletes a device pool given the pool ARN.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateDevicePool:
    get:
      summary: Create Device Pool
      description: Creates a device pool.
      operationId: createDevicePool
      x-api-path-slug: actioncreatedevicepool-get
      parameters:
      - in: query
        name: description
        description: The device pools description
        type: string
      - in: query
        name: name
        description: The device pools name
        type: string
      - in: query
        name: projectArn
        description: The ARN of the project for the device pool
        type: string
      - in: query
        name: rules
        description: The device pools rules
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
  /?Action=CreateProject:
    get:
      summary: Create Project
      description: Creates a new project.
      operationId: createProject
      x-api-path-slug: actioncreateproject-get
      parameters:
      - in: query
        name: name
        description: The projects name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Project
  /?Action=CreateRemoteAccessSession:
    get:
      summary: Create Remote Access Session
      description: Specifies and starts a remote access session.
      operationId: createRemoteAccessSession
      x-api-path-slug: actioncreateremoteaccesssession-get
      parameters:
      - in: query
        name: configuration
        description: The configuration information for the remote access session request
        type: string
      - in: query
        name: deviceArn
        description: The Amazon Resource Name (ARN) of the device for which you want
          to create a remote access session
        type: string
      - in: query
        name: name
        description: The name of the remote access session that you wish to create
        type: string
      - in: query
        name: projectArn
        description: The Amazon Resource Name (ARN) of the project for which you want
          to create a remote access session
        type: string
      responses:
        200:
          description: OK
      tags:
      - Remote Access Sessions
  /?Action=CreateUpload:
    get:
      summary: Create Upload
      description: Uploads an app or test scripts.
      operationId: createUpload
      x-api-path-slug: actioncreateupload-get
      parameters:
      - in: query
        name: contentType
        description: The uploads content type (for example, application/octet-stream)
        type: string
      - in: query
        name: name
        description: The uploads file name
        type: string
      - in: query
        name: projectArn
        description: The ARN of the project for the upload
        type: string
      - in: query
        name: type
        description: The uploads upload type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Upload
  /?Action=DeleteDevicePool:
    get:
      summary: Delete Device Pool
      description: Deletes a device pool given the pool ARN.
      operationId: deleteDevicePool
      x-api-path-slug: actiondeletedevicepool-get
      parameters:
      - in: query
        name: arn
        description: Represents the Amazon Resource Name (ARN) of the Device Farm
          device pool you wish to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
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