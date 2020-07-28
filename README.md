# POST API

POSTS API

npm install -g json-server

npm install -g newman

npm install -g swagger-node-codegen

snc swagger.yaml -o ./my-api --- (check version partner)

https://editor.swagger.io/?_ga=2.264995855.1427279939.1595917023-1350758995.1593199486

newman run https://www.getpostman.com/collections/cc6d91a9fbc6ef298da2 --env-var "baseUrl=https://df60aad5-2bc2-46ae-8eb4-db2d715a03b0.mock.pstmn.io"

https://www.apimatic.io/transformer/

prism mock -p 4010 myapi.yaml

npm install -g redoc-cli

redoc-cli bundle -o index.html myapi.yaml
