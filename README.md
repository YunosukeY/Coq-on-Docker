# Coq on Docker
以下が入る
- coqc
- coqide
- mathcomp/ssreflect

## 準備
X Window Systemをインストール・起動し，認証を無効化・接続を許可しておく

## ビルド
```
$ docker-compose build
```

## 起動
```
$ docker-compose up -d
```