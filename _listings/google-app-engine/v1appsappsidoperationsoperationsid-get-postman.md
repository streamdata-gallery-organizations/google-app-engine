{
  "info": {
    "name": "Google App Engine Admin API Get State",
    "_postman_id": "3e93b519-a77e-4234-b624-9a4363259a93",
    "description": "Gets the latest state of a long-running operation. Clients can use this method to poll the operation result at intervals as recommended by the API service.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "State",
      "item": [
        {
          "id": "3eef065c-db90-4bbf-b927-15d680e10753",
          "name": "appengine.apps.operations.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "appengine.googleapis.com",
              "path": [
                "v1/apps/:appsId/operations/:operationsId"
              ],
              "variable": [
                {
                  "id": "appsId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "operationsId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the latest state of a long-running operation. Clients can use this method to poll the operation result at intervals as recommended by the API service."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a39c34d3-5063-45d4-8fad-a760321141d0"
            }
          ]
        }
      ]
    }
  ]
}