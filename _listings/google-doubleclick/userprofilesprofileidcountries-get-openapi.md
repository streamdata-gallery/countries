---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Get Countries
  version: 1.0.0
  description: Retrieves a list of countries.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/countries:
    get:
      summary: Get Countries
      description: Retrieves a list of countries.
      operationId: dfareporting.countries.list
      x-api-path-slug: userprofilesprofileidcountries-get
      parameters:
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Country
  /userprofiles/{profileId}/countries/{dartId}:
    get:
      summary: Get Country
      description: Gets one country by ID.
      operationId: dfareporting.countries.get
      x-api-path-slug: userprofilesprofileidcountriesdartid-get
      parameters:
      - in: path
        name: dartId
        description: Country DART ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Country
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