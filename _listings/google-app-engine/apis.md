---
name: Google App Engine
x-slug: google-app-engine
description: 'Build modern web and mobile applications on an open cloud platform:
  bring your own language runtimes, frameworks, and third party libraries. Google
  App Engine is a fully managed platform that completely abstracts away infrastructure
  so you focus only on code. Go from zero to planet-scale and see why some of today&rsquo;s
  most successful companies power their applications on App Engine.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google App Engine
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google App Engine Admin - Create App
  x-api-slug: v1apps-post
  description: 'Creates an App Engine application for a Google Cloud Platform project.
    Required fields: id - The ID of the target Cloud Platform project. location -
    The region (https://cloud.google.com/appengine/docs/locations) where you want
    the App Engine application located.For more information about App Engine applications,
    see Managing Projects, Applications, and Billing (https://cloud.google.com/appengine/docs/python/console/).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1apps-post-openapi.md
- name: Google App Engine Admin - Get App
  x-api-slug: v1appsappsid-get
  description: Gets information about an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsid-get-openapi.md
- name: Google App Engine Admin - Update App
  x-api-slug: v1appsappsid-patch
  description: 'Updates the specified Application resource. You can update the following
    fields: auth_domain - Google authentication domain for controlling user access
    to the application. default_cookie_expiration - Cookie expiration policy for the
    application.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsid-patch-openapi.md
- name: Google App Engine Admin - Get App Locations
  x-api-slug: v1appsappsidlocations-get
  description: Lists information about the supported locations for this service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidlocations-get-openapi.md
- name: Google App Engine Admin - Get App Location
  x-api-slug: v1appsappsidlocationslocationsid-get
  description: Get information about a location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidlocationslocationsid-get-openapi.md
- name: Google App Engine Admin - Get Operations
  x-api-slug: v1appsappsidoperations-get
  description: 'Lists operations that match the specified filter in the request. If
    the server doesn''t support this method, it returns UNIMPLEMENTED.NOTE: the name
    binding below allows API services to override the binding to use different resource
    name schemes, such as users/*/operations.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidoperations-get-openapi.md
- name: Google App Engine Admin - Get State
  x-api-slug: v1appsappsidoperationsoperationsid-get
  description: Gets the latest state of a long-running operation. Clients can use
    this method to poll the operation result at intervals as recommended by the API
    service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidoperationsoperationsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidoperationsoperationsid-get-openapi.md
- name: Google App Engine Admin - Get Services
  x-api-slug: v1appsappsidservices-get
  description: Lists all the services in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservices-get-openapi.md
- name: Google App Engine Admin - Delete Service
  x-api-slug: v1appsappsidservicesservicesid-delete
  description: Deletes the specified service and all enclosed versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesid-delete-openapi.md
- name: Google App Engine Admin - Get Configuration
  x-api-slug: v1appsappsidservicesservicesid-get
  description: Gets the current configuration of the specified service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesid-get-openapi.md
- name: Google App Engine Admin - Update Configuration
  x-api-slug: v1appsappsidservicesservicesid-patch
  description: Updates the configuration of the specified service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesid-patch-openapi.md
- name: Google App Engine Admin - Get Versions
  x-api-slug: v1appsappsidservicesservicesidversions-get
  description: Lists the versions of a service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversions-get-openapi.md
- name: Google App Engine Admin - Deploy Version
  x-api-slug: v1appsappsidservicesservicesidversions-post
  description: Deploys code and resource files to a new version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversions-post-openapi.md
- name: Google App Engine Admin - Delete Version
  x-api-slug: v1appsappsidservicesservicesidversionsversionsid-delete
  description: Deletes an existing Version resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversionsversionsid-delete-openapi.md
- name: Google App Engine Admin - Get Version
  x-api-slug: v1appsappsidservicesservicesidversionsversionsid-get
  description: Gets the specified Version resource. By default, only a BASIC_VIEW
    will be returned. Specify the FULL_VIEW parameter to get the full resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversionsversionsid-get-openapi.md
- name: Google App Engine Admin - Update Version
  x-api-slug: v1appsappsidservicesservicesidversionsversionsid-patch
  description: 'Updates the specified Version resource. You can specify the following
    fields depending on the App Engine environment and type of scaling that the version
    resource uses: serving_status (https://cloud.google.com/appengine/docs/admin-api/reference/rest/v1/apps.services.versions#Version.FIELDS.serving_status):
    For Version resources that use basic scaling, manual scaling, or run in the App
    Engine flexible environment. instance_class (https://cloud.google.com/appengine/docs/admin-api/reference/rest/v1/apps.services.versions#Version.FIELDS.instance_class):
    For Version resources that run in the App Engine standard environment. automatic_scaling.min_idle_instances
    (https://cloud.google.com/appengine/docs/admin-api/reference/rest/v1/apps.services.versions#Version.FIELDS.automatic_scaling):
    For Version resources that use automatic scaling and run in the App Engine standard
    environment. automatic_scaling.max_idle_instances (https://cloud.google.com/appengine/docs/admin-api/reference/rest/v1/apps.services.versions#Version.FIELDS.automatic_scaling):
    For Version resources that use automatic scaling and run in the App Engine standard
    environment.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversionsversionsid-patch-openapi.md
- name: Google App Engine Admin - Get Instances
  x-api-slug: v1appsappsidservicesservicesidversionsversionsidinstances-get
  description: 'Lists the instances of a version.Tip: To aggregate details about instances
    over time, see the Stackdriver Monitoring API (https://cloud.google.com/monitoring/api/ref_v3/rest/v3/projects.timeSeries/list).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversionsversionsidinstances-get-openapi.md
- name: Google App Engine Admin - Stop Instance
  x-api-slug: v1appsappsidservicesservicesidversionsversionsidinstancesinstancesid-delete
  description: Stops a running instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversionsversionsidinstancesinstancesid-delete-openapi.md
- name: Google App Engine Admin - Get Instance
  x-api-slug: v1appsappsidservicesservicesidversionsversionsidinstancesinstancesid-get
  description: Gets instance information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversionsversionsidinstancesinstancesid-get-openapi.md
- name: Google App Engine Admin - Enable Debugging
  x-api-slug: v1appsappsidservicesservicesidversionsversionsidinstancesinstancesiddebug-post
  description: Enables debugging on a VM instance. This allows you to use the SSH
    command to connect to the virtual machine where the instance lives. While in "debug
    mode", the instance continues to serve live traffic. You should delete the instance
    when you are done debugging and then allow the system to take over and determine
    if another instance should be started.Only applicable for instances in App Engine
    flexible environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidservicesservicesidversionsversionsidinstancesinstancesiddebug-post-openapi.md
- name: Google App Engine Admin - Repair App
  x-api-slug: v1appsappsidrepair-post
  description: Recreates the required App Engine features for the specified App Engine
    application, for example a Cloud Storage bucket or App Engine service account.
    Use this method if you receive an error message about a missing feature, for example,
    Error retrieving the App Engine service account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-app-engine/master/_listings/google-app-engine/v1appsappsidrepair-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.api.discovery.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.app.engine.stack.network
- type: x-code-page
  url: https://cloud.google.com/appengine/docs/admin-api/client-libraries
- type: x-developer
  url: https://cloud.google.com/appengine/docs/admin-api/
- type: x-documentation
  url: https://cloud.google.com/appengine/docs/admin-api/apis
- type: x-getting-started
  url: https://cloud.google.com/appengine/docs/admin-api/getting-started/
- type: x-how-to-guides
  url: https://cloud.google.com/appengine/docs/admin-api/how-to
- type: x-launcher
  url: https://cloud.google.com/launcher/
- type: x-pricing
  url: https://cloud.google.com/pricing/
- type: x-sla
  url: https://cloud.google.com/appengine/sla
- type: x-website
  url: https://cloud.google.com/appengine/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---