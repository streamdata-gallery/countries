---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API List Countries
  description: List Countries
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /config-media-live/v1/live/utils/countries:
    get:
      summary: List Countries
      description: List Countries
      operationId: configmedialivev1liveutilscountries
      x-api-path-slug: configmedialivev1liveutilscountries-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Utils
      - Countries
  /config-media-security/v1/security/countries:
    get:
      summary: List Countries
      description: List Countries
      operationId: configmediasecurityv1securitycountries
      x-api-path-slug: configmediasecurityv1securitycountries-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Countries
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