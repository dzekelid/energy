---
name: Weatherbit.io
x-slug: weatherbit-io
description: Our Weather API is the most powerful Weather data API on the web. Sign
  up for our free Weather API, and upgrade as your weather data needs grow!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
x-kinRank: "8"
x-alexaRank: "1016253"
tags: Energy
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/energy/master/_listings/weatherbit-io/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit - Get History Energy Bbox Lat1 Lat1 &lon1 Lon1 &lat2 Lat2 &lon2
    Lon2
  x-api-slug: historyenergybboxlat1lat1lon1lon1lat2lat2lon2lon2-get
  description: 'Returns aggregate energy specific historical weather fields, over
    a specified time period. Supply a bounding box ex: lat1=40&lon1=-78&lat2=38&lon2=-80.
    This API will return UP TO 150 stations, aggregated by the specified time period
    start_date to end_date.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/energy/master/_listings/weatherbit-io/historyenergybboxlat1lat1lon1lon1lat2lat2lon2lon2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/energy/master/_listings/weatherbit-io/historyenergybboxlat1lat1lon1lon1lat2lat2lon2lon2-get-openapi.md
- name: Weatherbit - Get History Energy Lat & Lon
  x-api-slug: historyenergylatlatlonlon-get
  description: Returns aggregate energy specific historical weather fields, over a
    specified time period.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/energy/master/_listings/weatherbit-io/historyenergylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/energy/master/_listings/weatherbit-io/historyenergylatlatlonlon-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://weather.underground.api.gallery.streamdata.io
- type: x-api-stack
  url: http://weatherbit.io.stack.network
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-crunchbase
  url: https://crunchbase.com/organization/product/weather-it-
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-email
  url: support@weatherbit.io
- type: x-github
  url: https://github.com/weatherbit
- type: x-pricing
  url: https://www.weatherbit.io/pricing
- type: x-twitter
  url: https://twitter.com/weatherbitio
- type: x-website
  url: http://weatherbit.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---