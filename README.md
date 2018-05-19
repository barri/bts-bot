# bts-bot

http://balancerensa.net/

## 実装されているコマンド

- `/echo`: オウム返しする
- `/usagi` 「かわいい」と返す

## 手元で動かす

- Ruby 2.5+
- 環境変数 `CLIENT_ID` に Discord bot のクライアント ID を、環境変数 `SECRET_TOKEN` にトークンを入れた状態にする

```
$ bundle install -j4
$ bundle exec ruby main.rb
```

## Docker イメージ

bTS メンバーなら誰でも push できるようにしたい..

```
$ docker build -t mozamimy/bts-bot .
$ docker push mozamimy/bts-bot:latest
```

## デプロイ

とりあえず [Arukas](https://arukas.io/) で雑に動かしてます。bTS メンバーなら誰でもデプロイできる仕組みにしたい。

## ライセンス

MIT
