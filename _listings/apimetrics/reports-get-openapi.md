---
swagger: "2.0"
x-collection-name: APImetrics
x-complete: 0
info:
  title: APIMetrics List all Reports
  version: 1.0.0
  description: List all Reports
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reports/:
    get:
      summary: List all Reports
      description: List all Reports
      operationId: listAllReports
      x-api-path-slug: reports-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Reports
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