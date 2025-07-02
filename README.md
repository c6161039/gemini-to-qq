# 用napcat 来让你的扣扣小号变成gemini来对话吧

## config.ini
```ini
;在napcat中创建http服务器和websocket服务器
[http]
;http服务器发信
url = http://127.0.0.1:3000
urlToken = token

[websocket]
;ws服务器发信
wsURL = ws://127.0.0.1:3001/
wsToken = token

[gemini]
;这里是gemini的api
apiKey = geminiapi
```

## prompt.txt
```
如题 这里是提示词
例:你是原神里的重云 主要语言是中文 简短的话
```


```
go build main.go
```
