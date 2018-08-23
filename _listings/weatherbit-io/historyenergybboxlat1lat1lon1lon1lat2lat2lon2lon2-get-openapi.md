---
swagger: "2.0"
x-collection-name: Weatherbit.io
x-complete: 0
info:
  title: Weatherbit Get History Energy Bbox Lat1 Lat1 &lon1 Lon1 &lat2 Lat2 &lon2
    Lon2
  description: 'Returns aggregate energy specific historical weather fields, over
    a specified time period. Supply a bounding box ex: lat1=40&lon1=-78&lat2=38&lon2=-80.
    This API will return UP TO 150 stations, aggregated by the specified time period
    start_date to end_date.'
  version: 2.0.0
host: api.weatherbit.io
basePath: /v2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /history/energy/bbox?lat1={lat1}&lon1={lon1}&lat2={lat2}&lon2={lon2}:
    get:
      summary: Get History Energy Bbox Lat1 Lat1 &lon1 Lon1 &lat2 Lat2 &lon2 Lon2
      description: 'Returns aggregate energy specific historical weather fields, over
        a specified time period. Supply a bounding box ex: lat1=40&lon1=-78&lat2=38&lon2=-80.
        This API will return UP TO 150 stations, aggregated by the specified time
        period start_date to end_date.'
      operationId: returns-aggregate-energy-specific-historical-weather-fields-over-a-specified-time-period-supply-a-bo
      x-api-path-slug: historyenergybboxlat1lat1lon1lon1lat2lat2lon2lon2-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: path
        name: lat1
        description: Latitude of upper left corner
      - in: path
        name: lat2
        description: Latitude of lower right corner
      - in: path
        name: lon1
        description: Longitude of upper left corner
      - in: path
        name: lon2
        description: Longitude of lower right corner
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - History
      - Energy
      - Bbox
      - Lat1
      - Lat1
      - '&lon1'
      - Lon1
      - '&lat2'
      - Lat2
      - '&lon2'
      - Lon2
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