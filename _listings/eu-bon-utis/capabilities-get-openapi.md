---
swagger: "2.0"
x-collection-name: EU BON UTIS
x-complete: 0
info:
  title: EU BON UTIS Capabilities
  description: Capabilities
  termsOfService: https://www.biodiversitycatalogue.org/services/79
  version: "1.0"
host: cybertaxonomy.eu
basePath: /eu-bon/utis/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /capabilities:
    get:
      summary: Capabilities
      description: Capabilities
      operationId: getCapabilities
      x-api-path-slug: capabilities-get
      responses:
        200:
          description: OK
      tags:
      - Capabilities
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