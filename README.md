# Wordpressのローカル開発環境構築用docker-compose.ymlファイル

## 使い方

1. このレポジトリをローカルにクローンする
```
git clone git@github.com:HiroshiJorrvaskr/WordpressLocal.git
```

2. WordpressLocalフォルダに移動する
```
cd WordpressLocal
```

3. docker-compose.ymlを起動する
```
sudo docker-compose up -d
```

4. ブラウザでWordpressサイトにアクセスする
```
localhost:8000
```

5. 終了するときは以下のコマンドを打つ
```
docker-compose down
```