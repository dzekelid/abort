---
swagger: "2.0"
x-collection-name: AWS S3
x-complete: 0
info:
  title: AWS S3 Abort Multipart Upload
  version: 1.0.0
  description: This operation aborts a multipart upload
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ObjectName?uploadId=UploadId:
    delete:
      summary: Abort Multipart Upload
      description: This operation aborts a multipart upload
      operationId: abort-multipart-upload
      x-api-path-slug: objectnameuploadiduploadid-delete
      responses:
        200:
          description: OK
      tags:
      - Abort
      - Multipart
      - Upload
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