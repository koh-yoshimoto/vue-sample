# Vue.js with Docker

### コンテナを起動する

---
`-d` オプションでコンテナをバックグラウンドで起動する
```
docker compose up -d
```

### コンテナに接続する

---
コンテナ内に入る
```
docker compose exec web /bin/bash
```

### プロジェクトを作成する

---
```
vue create .
```

### サーバを起動する

---
```
yarn serve
```
http://localhost:8080/ でアクセス

### コンテナに入らずVueを起動

---
```
docker compose exec app yarn serve
```
