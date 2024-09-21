# MockServer

This repository showcases use of [↑ MockServer](https://www.mock-server.com). 

[↑ JSON examples](https://github.com/mock-server/mockserver/blob/master/mockserver-examples/json_examples.md).

## Running

Run infrastructure:

```bash
make run-infrastructure
```

MockServer UI : <http://localhost:2020/mockserver/dashboard>.

Example of cUrl call to MockServer:

```bash
curl --location 'http://localhost:2020/api/users/get' \
--header 'Content-Type: application/json' \
--data '{
    "path": "/your_service/the/path",
    "service": "your_service"
}'
```

