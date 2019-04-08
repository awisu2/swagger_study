swagger study
=============

`docker run --rm -p 8080:8080 swaggerapi/swagger-ui`

bin
---

- run swagger-ui: `sh bin ui`
- run swagger-editor: `sh bin editor`

what is swagger
---------------

api document total support tools. [The Best APIs are Built with Swagger Tools \| Swagger](https://swagger.io/)  
but it can't create stand alone document. only on network.

### famous resources

- swagger-spec: syntax of swagger.
  - it's can type of json and yaml.
- swagger-editor: editor, it's can read and edit document type of swagger-spec.
  - it can import local file, but can't save directory need download.
- swagger-ui: read and show document type of swagger-spec.
  - it can read only document on the network.

swagger ui
----------

### 読み込むドキュメントをURLパラメータで変更する方法

`${host}?url=${swagger spec url}`

### api blueprintからの変換

apib2swagger -i ${api blueprint markdown file} -o ${output json}
