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
