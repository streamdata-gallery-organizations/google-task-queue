{
  "info": {
    "name": "Google Task Queue API Get Task Queues",
    "_postman_id": "bd9d2bdc-f9e4-47fa-9cf7-59bc64686e83",
    "description": "Get detailed information about a TaskQueue.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "task queues",
      "item": [
        {
          "id": "0b1c0491-3935-4db4-88b5-1bc5126975d5",
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
            "description": "Get detailed information about a TaskQueue"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90e1ba53-51b8-40ca-b2d1-f40d0d5d3143"
            }
          ]
        }
      ]
    }
  ]
}