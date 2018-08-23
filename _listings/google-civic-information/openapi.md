---
swagger: "2.0"
x-collection-name: Google Civic Information
x-complete: 1
info:
  title: Google Civic Information
  description: provides-polling-places-early-vote-locations-contest-data-election-officials-and-government-representatives-for-u-s--residential-addresses-
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /civicinfo/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /elections:
    get:
      summary: List Elections
      description: List of available elections to query.
      operationId: civicinfo.elections.electionQuery
      x-api-path-slug: elections-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Election
---