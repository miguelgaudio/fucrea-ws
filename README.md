Con un WS (y pasando a json con npmjs)
	yaml2json swagger.yaml > swagger.json
	curl -X POST -d @swagger.json -H 'Content-Type:application/json' http://online.swagger.io/validator/debug

O con swagger-cli
	swagger validate swagger.yaml

