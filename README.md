# About

nginx リバースプロキシ
Express
ngrok

`ngrok`を使って、コンテナを外部公開できます。

# How to use

`src`に`express`プロジェクトを配置してください

下記コマンドから起動します。

```
docker-compose up -d --build
```

`localhost:4040`から`ngrok`でトンネルされて生成されたリンクが表示されます。

[認証が必要な機能](https://hub.docker.com/r/wernight/ngrok)を用いる場合、  
`docker-compose.yml`の`environment`箇所の`NGROK_AUTH: ${NGROK_AUTH}`のコメントアウトを外してください
