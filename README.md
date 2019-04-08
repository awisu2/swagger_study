
`docker run --rm -p 8080:8080 swaggerapi/swagger-ui`


swagger ui
----------

### 読み込むドキュメントをURLパラメータで変更する方法

`${host}?url=${swagger spec url}`

### api blueprintからの変換

apib2swagger -i ${api blueprint markdown file} -o ${output json}
