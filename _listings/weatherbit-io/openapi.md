---
swagger: "2.0"
x-collection-name: Weatherbit.io
x-complete: 1
info:
  title: Weatherbit
  description: this-is-the-documentation-for-the-weatherbit-api---the-base-url-for-the-api-is-httpapi-weatherbit-iov2-0httpapi-weatherbit-iov2-0-or-httpsapi-weatherbit-iov2-0httpapi-weatherbit-iov2-0--below-is-the-swagger-ui-documentation-for-the-api--all-api-requests-require-the-key-parameter---------an-example-for-a-5-day-forecast-for-london-uk-would-be-httpapi-weatherbit-iov2-0forecast3hourlycitylondoncountryuk
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
  /history/energy?lat={lat}&lon={lon}:
    get:
      summary: Get History Energy Lat & Lon
      description: Returns aggregate energy specific historical weather fields, over
        a specified time period.
      operationId: returns-aggregate-energy-specific-historical-weather-fields-over-a-specified-time-period
      x-api-path-slug: historyenergylatlatlonlon-get
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
        name: lat
        description: Latitude component of location
      - in: path
        name: lon
        description: Longitude component of location
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
      - Lat
      - Lat
      - '&lon'
      - Lon
---