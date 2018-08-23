---
swagger: "2.0"
x-collection-name: AWS S3
x-complete: 1
info:
  title: No Title
  version: 1.0.0
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
---