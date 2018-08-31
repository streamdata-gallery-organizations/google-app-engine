---
swagger: "2.0"
x-collection-name: Google App Engine
x-complete: 0
info:
  title: Google App Engine Admin API Create App
  description: 'Creates an App Engine application for a Google Cloud Platform project.
    Required fields: id - The ID of the target Cloud Platform project. location -
    The region (https://cloud.google.com/appengine/docs/locations) where you want
    the App Engine application located.For more information about App Engine applications,
    see Managing Projects, Applications, and Billing (https://cloud.google.com/appengine/docs/python/console/).'
  contact:
    name: Google
    url: https://google.com
  version: v1
host: appengine.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/apps:
    post:
      summary: Create App
      description: 'Creates an App Engine application for a Google Cloud Platform
        project. Required fields: id - The ID of the target Cloud Platform project.
        location - The region (https://cloud.google.com/appengine/docs/locations)
        where you want the App Engine application located.For more information about
        App Engine applications, see Managing Projects, Applications, and Billing
        (https://cloud.google.com/appengine/docs/python/console/).'
      operationId: appengine.apps.create
      x-api-path-slug: v1apps-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Application
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