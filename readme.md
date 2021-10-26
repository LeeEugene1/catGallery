api

# root 내용 가져오기(목록)
* https://zl3m4qq0l9.execute-api.ap-northeast-2.amazonaws.com/dev
* method: GET
```
[{"id":"1","name":"노란고양이","type":"DIRECTORY","filePath":null,"parent":null},{"id":"3","name":"까만고양이","type":"DIRECTORY","filePath":null,"parent":null},{"id":"10","name":"고등어무늬 고양이","type":"DIRECTORY","filePath":null,"parent":null},{"id":"13","name":"삼색이 고양이","type":"DIRECTORY","filePath":null,"parent":null},{"id":"14","name":"회색고양이","type":"DIRECTORY","filePath":null,"parent":null},{"id":"20","name":"하얀고양이","type":"DIRECTORY","filePath":"/images/20201218_002047.jpg","parent":null}]
```

# 특정 디렉토리에 속하는 파일 / 디렉토리 불러오기
* https://zl3m4qq0l9.execute-api.ap-northeast-2.amazonaws.com/dev/:nodeId
* method: GET
