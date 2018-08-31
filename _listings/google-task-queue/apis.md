---
name: Google Task Queue
x-slug: google-task-queue
description: The Task Queue API lets applications perform work, called tasks, asynchronously
  outside of a user request. If an app needs to execute work in the background, it
  adds tasks to task queues. The tasks are executed later, by scalable App Engine
  worker services in your application.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Task Queue
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/apis.md
specificationVersion: "0.14"
apis:
- name: TaskQueue - Get Task Queues
  x-api-slug: projecttaskqueuestaskqueue-get
  description: Get detailed information about a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google APIs, Tasks, Jobs, Orchestration, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueue-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueue-get-openapi.md
- name: TaskQueue - Get Tasks
  x-api-slug: projecttaskqueuestaskqueuetasks-get
  description: List Tasks in a TaskQueue
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google APIs, Tasks, Jobs, Orchestration, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetasks-get-openapi.md
- name: TaskQueue - Insert Task
  x-api-slug: projecttaskqueuestaskqueuetasks-post
  description: Insert a new task in a TaskQueue
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google APIs, Tasks, Jobs, Orchestration, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetasks-post-openapi.md
- name: TaskQueue - Lease Task
  x-api-slug: projecttaskqueuestaskqueuetaskslease-post
  description: Lease 1 or more tasks from a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google APIs, Tasks, Jobs, Orchestration, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskslease-post-openapi.md
- name: TaskQueue - Delete Task
  x-api-slug: projecttaskqueuestaskqueuetaskstask-delete
  description: Delete a task from a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google APIs, Tasks, Jobs, Orchestration, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskstask-delete-openapi.md
- name: TaskQueue - Get Task
  x-api-slug: projecttaskqueuestaskqueuetaskstask-get
  description: Get a particular task from a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google APIs, Tasks, Jobs, Orchestration, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskstask-get-openapi.md
- name: TaskQueue - Update Task
  x-api-slug: projecttaskqueuestaskqueuetaskstask-patch
  description: Update tasks that are leased out of a TaskQueue. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google APIs, Tasks, Jobs, Orchestration, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskstask-patch-openapi.md
- name: TaskQueue - Update Task
  x-api-slug: projecttaskqueuestaskqueuetaskstask-post
  description: Update tasks that are leased out of a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google APIs, Tasks, Jobs, Orchestration, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskstask-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.tag.manager.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.task.queue.stack.network
- type: x-code
  url: https://cloud.google.com/appengine/docs/standard/python/taskqueue/rest/libraries
- type: x-documentation
  url: https://cloud.google.com/appengine/docs/standard/python/taskqueue/rest/
- type: x-performance
  url: https://cloud.google.com/appengine/docs/standard/python/taskqueue/rest/performance
- type: x-website
  url: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---