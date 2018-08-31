{
  "info": {
    "name": "Google Task Queue API Get Tasks",
    "_postman_id": "4a01ad0d-c89d-4715-9dd3-a66cb4a0014b",
    "description": "List Tasks in a TaskQueue",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Task Queues",
      "item": [
        {
          "id": "56bed997-8375-4898-b1d6-1d098f58c28b",
          "name": "taskqueue.taskqueues.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "taskqueue",
                "v1beta2",
                "projects",
                ":project/taskqueues/:taskqueue"
              ],
              "query": [
                {
                  "key": "getStats",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "project",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "taskqueue",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get detailed information about a TaskQueue."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30d9a537-4ebc-4a7d-98a4-8d0ffc028ef0"
            }
          ]
        }
      ]
    },
    {
      "name": "Task",
      "item": [
        {
          "id": "b5392c88-d9ad-44af-940e-087820c6d116",
          "name": "taskqueue.tasks.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "taskqueue",
                "v1beta2",
                "projects",
                ":project/taskqueues/:taskqueue/tasks"
              ],
              "variable": [
                {
                  "id": "project",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "taskqueue",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Tasks in a TaskQueue"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b363db1-c628-4bc9-94c4-54529ef6ba1d"
            }
          ]
        }
      ]
    }
  ]
}