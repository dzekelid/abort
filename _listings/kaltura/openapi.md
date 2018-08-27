swagger: "2.0"
x-collection-name: Kaltura
x-complete: 1
info:
  title: Kaltura VPaaS
  description: building-video-experiences-consists-of-ingesting-media-files-playing-back-videos-and-reviewing-usage-and-engagement-analytics--in-between-there-is-a-world-of-nuances-required-for-your-unique-usecase-and-application--kaltura-vpaas-is-built-on-the-principles-of-atomic-services-sdks-and-tools-that-allow-you-full-control-and-flexibility-over-every-element-and-process-in-your-medias-life-cycle-
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/bulkupload/action/abort:
    get:
      summary: Get Service Bulkupload Action Abort
      description: Aborts the bulk upload and all its child jobs
      operationId: bulkUpload.abort
      x-api-path-slug: servicebulkuploadactionabort-get
      parameters:
      - in: query
        name: id
        description: job id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Bulkupload
      - Action
      - Abort
  /service/bulkupload_bulk/action/abort:
    get:
      summary: Get Service Bulkupload Bulk Action Abort
      description: Aborts the bulk upload and all its child jobs
      operationId: bulk.abort
      x-api-path-slug: servicebulkupload-bulkactionabort-get
      parameters:
      - in: query
        name: id
        description: job id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Bulkupload
      - Bulk
      - Action
      - Abort
  /service/businessprocessnotification_businessprocesscase/action/abort:
    get:
      summary: Get Service Businessprocessnotification Businessprocesscase Action
        Abort
      description: Abort business-process case
      operationId: businessProcessCase.abort
      x-api-path-slug: servicebusinessprocessnotification-businessprocesscaseactionabort-get
      parameters:
      - in: query
        name: businessProcessStartNotificationTemplateId
      - in: query
        name: No Name
      - in: query
        name: objectId
      - in: query
        name: objectType
        description: 'Enum Type: `KalturaEventNotificationEventObjectType`'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocesscase
      - Action
      - Abort