---
name: AWS Device Farm
x-slug: aws-device-farm
description: AWS Device Farm is an app testing service that lets you test and interact
  with your Android, iOS, and web apps on many devices at once, or reproduce issues
  on a device in real time. View video, screenshots, logs, and performance data to
  pinpoint and fix issues before shipping your app.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS Device Farm
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Device Farm API Create Device Pool
  x-api-slug: aws-device-farm-api
  description: Creates a device pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=CreateDevicePool
  tags: Device Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actioncreatedevicepool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actioncreatedevicepool-get-openapi.md
- name: AWS Device Farm API Create Project
  x-api-slug: aws-device-farm-api
  description: Creates a new project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=CreateProject
  tags: Project
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actioncreateproject-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actioncreateproject-get-openapi.md
- name: AWS Device Farm API Create Remote Access Session
  x-api-slug: aws-device-farm-api
  description: Specifies and starts a remote access session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=CreateRemoteAccessSession
  tags: Remote Access Sessions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actioncreateremoteaccesssession-get-openapi.md
- name: AWS Device Farm API Create Upload
  x-api-slug: aws-device-farm-api
  description: Uploads an app or test scripts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=CreateUpload
  tags: Upload
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actioncreateupload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actioncreateupload-get-openapi.md
- name: AWS Device Farm API Delete Device Pool
  x-api-slug: aws-device-farm-api
  description: Deletes a device pool given the pool ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=DeleteDevicePool
  tags: Device Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiondeletedevicepool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiondeletedevicepool-get-openapi.md
- name: AWS Device Farm API Delete Project
  x-api-slug: aws-device-farm-api
  description: Deletes an AWS Device Farm project, given the project ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=DeleteProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiondeleteproject-get-openapi.md
- name: AWS Device Farm API Delete Remote Access Session
  x-api-slug: aws-device-farm-api
  description: Deletes a completed remote access session and its results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=DeleteRemoteAccessSession
  tags: Remote Access Sessions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiondeleteremoteaccesssession-get-openapi.md
- name: AWS Device Farm API Delete Run
  x-api-slug: aws-device-farm-api
  description: Deletes the run, given the run ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=DeleteRun
  tags: Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiondeleterun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiondeleterun-get-openapi.md
- name: AWS Device Farm API Delete Upload
  x-api-slug: aws-device-farm-api
  description: Deletes an upload given the upload ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=DeleteUpload
  tags: Uploads
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiondeleteupload-get-openapi.md
- name: AWS Device Farm API Get Account Settings
  x-api-slug: aws-device-farm-api
  description: Returns the number of unmetered iOS and/or unmetered Android devices
    that have been purchased by the account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetAccountSettings
  tags: Account Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetaccountsettings-get-openapi.md
- name: AWS Device Farm API Get Device
  x-api-slug: aws-device-farm-api
  description: Gets information about a unique device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetDevice
  tags: Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetdevice-get-openapi.md
- name: AWS Device Farm API Get Device Pool
  x-api-slug: aws-device-farm-api
  description: Gets information about a device pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetDevicePool
  tags: Device Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetdevicepool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetdevicepool-get-openapi.md
- name: AWS Device Farm API Get Device Pool Compatibility
  x-api-slug: aws-device-farm-api
  description: Gets information about compatibility with a device pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetDevicePoolCompatibility
  tags: Device Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetdevicepoolcompatibility-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetdevicepoolcompatibility-get-openapi.md
- name: AWS Device Farm API Get Job
  x-api-slug: aws-device-farm-api
  description: Gets information about a job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetJob
  tags: Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetjob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetjob-get-openapi.md
- name: AWS Device Farm API Get Offering Status
  x-api-slug: aws-device-farm-api
  description: Gets the current status and future status of all offerings purchased
    by an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetOfferingStatus
  tags: Offering Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetofferingstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetofferingstatus-get-openapi.md
- name: AWS Device Farm API Get Project
  x-api-slug: aws-device-farm-api
  description: Gets information about a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetproject-get-openapi.md
- name: AWS Device Farm API Get Remote Access Session
  x-api-slug: aws-device-farm-api
  description: Returns a link to a currently running remote access session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetRemoteAccessSession
  tags: Remote Access Sessions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetremoteaccesssession-get-openapi.md
- name: AWS Device Farm API Get Run
  x-api-slug: aws-device-farm-api
  description: Gets information about a run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetRun
  tags: Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetrun-get-openapi.md
- name: AWS Device Farm API Get Suite
  x-api-slug: aws-device-farm-api
  description: Gets information about a suite.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetSuite
  tags: Suites
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetsuite-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetsuite-get-openapi.md
- name: AWS Device Farm API Get Test
  x-api-slug: aws-device-farm-api
  description: Gets information about a test.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetTest
  tags: Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongettest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongettest-get-openapi.md
- name: AWS Device Farm API Get Upload
  x-api-slug: aws-device-farm-api
  description: Gets information about an upload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetUpload
  tags: Upload
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetupload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actiongetupload-get-openapi.md
- name: AWS Device Farm API Install To Remote Access Session
  x-api-slug: aws-device-farm-api
  description: Installs an application to the device in a remote access session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=InstallToRemoteAccessSession
  tags: Remote Access Sessions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actioninstalltoremoteaccesssession-get-openapi.md
- name: AWS Device Farm API List Artifacts
  x-api-slug: aws-device-farm-api
  description: Gets information about artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListArtifacts
  tags: Artifacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistartifacts-get-openapi.md
- name: AWS Device Farm API List Device Pools
  x-api-slug: aws-device-farm-api
  description: Gets information about device pools.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListDevicePools
  tags: Device Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistdevicepools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistdevicepools-get-openapi.md
- name: AWS Device Farm API List Devices
  x-api-slug: aws-device-farm-api
  description: Gets information about unique device types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListDevices
  tags: Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistdevices-get-openapi.md
- name: AWS Device Farm API List Jobs
  x-api-slug: aws-device-farm-api
  description: Gets information about jobs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListJobs
  tags: Jobs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistjobs-get-openapi.md
- name: AWS Device Farm API List Offerings
  x-api-slug: aws-device-farm-api
  description: Returns a list of products or offerings that the user can manage through
    the API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListOfferings
  tags: Offerings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistofferings-get-openapi.md
- name: AWS Device Farm API List Offering Transactions
  x-api-slug: aws-device-farm-api
  description: |-
    Returns a list of all historical purchases, renewals, and system renewal transactions for an
          AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListOfferingTransactions
  tags: Offering Transactions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistofferingtransactions-get-openapi.md
- name: AWS Device Farm API List Projects
  x-api-slug: aws-device-farm-api
  description: Gets information about projects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListProjects
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistprojects-get-openapi.md
- name: AWS Device Farm API List Remote Access Sessions
  x-api-slug: aws-device-farm-api
  description: Returns a list of all currently running remote access sessions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListRemoteAccessSessions
  tags: Remote Access Sessions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistremoteaccesssessions-get-openapi.md
- name: AWS Device Farm API List Runs
  x-api-slug: aws-device-farm-api
  description: Gets information about runs, given an AWS Device Farm project ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListRuns
  tags: Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistruns-get-openapi.md
- name: AWS Device Farm API List Samples
  x-api-slug: aws-device-farm-api
  description: Gets information about samples, given an AWS Device Farm project ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListSamples
  tags: Samples
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistsamples-get-openapi.md
- name: AWS Device Farm API List Suites
  x-api-slug: aws-device-farm-api
  description: Gets information about suites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListSuites
  tags: Suites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistsuites-get-openapi.md
- name: AWS Device Farm API List Tests
  x-api-slug: aws-device-farm-api
  description: Gets information about tests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListTests
  tags: Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlisttests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlisttests-get-openapi.md
- name: AWS Device Farm API List Unique Problems
  x-api-slug: aws-device-farm-api
  description: Gets information about unique problems.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListUniqueProblems
  tags: Unique Problems
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistuniqueproblems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistuniqueproblems-get-openapi.md
- name: AWS Device Farm API List Uploads
  x-api-slug: aws-device-farm-api
  description: Gets information about uploads, given an AWS Device Farm project ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListUploads
  tags: Uploads
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionlistuploads-get-openapi.md
- name: AWS Device Farm API Purchase Offering
  x-api-slug: aws-device-farm-api
  description: Immediately purchases offerings for an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=PurchaseOffering
  tags: Offerings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionpurchaseoffering-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionpurchaseoffering-get-openapi.md
- name: AWS Device Farm API Renew Offering
  x-api-slug: aws-device-farm-api
  description: |-
    Explicitly sets the quantity of devices to renew for an offering, starting from the
          effectiveDate of the next period.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=RenewOffering
  tags: Offerings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionrenewoffering-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionrenewoffering-get-openapi.md
- name: AWS Device Farm API Schedule Run
  x-api-slug: aws-device-farm-api
  description: Schedules a run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ScheduleRun
  tags: Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionschedulerun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionschedulerun-get-openapi.md
- name: AWS Device Farm API Stop Remote Access Session
  x-api-slug: aws-device-farm-api
  description: Ends a specified remote access session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=StopRemoteAccessSession
  tags: Remote Access Sessions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionstopremoteaccesssession-get-openapi.md
- name: AWS Device Farm API Stop Run
  x-api-slug: aws-device-farm-api
  description: Initiates a stop request for the current test run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=StopRun
  tags: Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionstoprun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionstoprun-get-openapi.md
- name: AWS Device Farm API Update Device Pool
  x-api-slug: aws-device-farm-api
  description: Modifies the name, description, and rules in a device pool given the
    attributes and the pool ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=UpdateDevicePool
  tags: Device Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionupdatedevicepool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionupdatedevicepool-get-openapi.md
- name: AWS Device Farm API Update Project
  x-api-slug: aws-device-farm-api
  description: Modifies the specified project name, given the project ARN and a new
    name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=UpdateProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/actionupdateproject-get-openapi.md
- name: AWS Device Farm API
  x-api-slug: aws-device-farm-api
  description: AWS Device Farm is an app testing service that lets you test and interact
    with your Android, iOS, and web apps on many devices at once, or reproduce issues
    on a device in real time. View video, screenshots, logs, and performance data
    to pinpoint and fix issues before shipping your app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: :///
  tags: AWS Device Farm
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-device-farm/master/_listings/aws-device-farm/openapi.md
x-common:
- type: x-blog
  url: https://aws.amazon.com/blogs/mobile/tag/aws-device-farm/
- type: x-concepts
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/concepts.html
- type: x-documentation
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/api-ref.html
- type: x-documentation
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/cli-ref.html
- type: x-limits
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/limits.html
- type: x-logging
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/cloudtrail.html
- type: x-plugins
  url: https://github.com/awslabs?q=aws-device-farm
- type: x-faq
  url: https://aws.amazon.com/device-farm/faq
- type: x-pricing
  url: https://aws.amazon.com/device-farm/pricing
- type: x-website
  url: https://aws.amazon.com/device-farm/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---