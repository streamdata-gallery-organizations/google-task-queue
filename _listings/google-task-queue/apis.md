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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/apis.md
specificationVersion: "0.14"
apis:
- name: Google Task Queue API Get Task Queues
  x-api-slug: google-task-queue-api
  description: Get detailed information about a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects//{project}/taskqueues/{taskqueue}
  tags: Task Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueue-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueue-get-openapi.md
- name: Google Task Queue API Get Tasks
  x-api-slug: google-task-queue-api
  description: List Tasks in a TaskQueue
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects//{project}/taskqueues/{taskqueue}/tasks
  tags: Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetasks-get-openapi.md
- name: Google Task Queue API Insert Task
  x-api-slug: google-task-queue-api
  description: Insert a new task in a TaskQueue
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects//{project}/taskqueues/{taskqueue}/tasks
  tags: Task
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetasks-post-openapi.md
- name: Google Task Queue API Lease Task
  x-api-slug: google-task-queue-api
  description: Lease 1 or more tasks from a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects//{project}/taskqueues/{taskqueue}/tasks/lease
  tags: Task
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskslease-post-openapi.md
- name: Google Task Queue API Delete Task
  x-api-slug: google-task-queue-api
  description: Delete a task from a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects//{project}/taskqueues/{taskqueue}/tasks/{task}
  tags: Task
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskstask-delete-openapi.md
- name: Google Task Queue API Get Task
  x-api-slug: google-task-queue-api
  description: Get a particular task from a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects//{project}/taskqueues/{taskqueue}/tasks/{task}
  tags: Task
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskstask-get-openapi.md
- name: Google Task Queue API Update Task
  x-api-slug: google-task-queue-api
  description: Update tasks that are leased out of a TaskQueue. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects//{project}/taskqueues/{taskqueue}/tasks/{task}
  tags: Task
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskstask-patch-openapi.md
- name: Google Task Queue API Update Task
  x-api-slug: google-task-queue-api
  description: Update tasks that are leased out of a TaskQueue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects//{project}/taskqueues/{taskqueue}/tasks/{task}
  tags: Task
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/projecttaskqueuestaskqueuetaskstask-post-openapi.md
- name: Google Task Queue API
  x-api-slug: google-task-queue-api
  description: The Task Queue API lets applications perform work, called tasks, asynchronously
    outside of a user request. If an app needs to execute work in the background,
    it adds tasks to task queues. The tasks are executed later, by scalable App Engine
    worker services in your application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hands-on-app-engine-11-638.jpg
  humanURL: https://cloud.google.com/appengine/docs/standard/python/taskqueue/
  baseURL: ://www.googleapis.com//taskqueue/v1beta2/projects
  tags: Google Task Queue
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-task-queue/master/_listings/google-task-queue/openapi.md
x-common:
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