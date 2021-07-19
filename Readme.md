# Auth0 Single Page Application写経

## はじめに
本リポジトリはauth0の[spa quick start](https://auth0.com/docs/quickstart/spa/vanillajs) を写経したものです。

## 前提条件

1. 以下ソフトがインストールされていること

  * node.js(v16.3.0以上)
  * npm(7.15.1以上)

2. auth0のアカウントを所持していること
3. 「Configure Auth0」の作業を実施していること
  https://auth0.com/docs/quickstart/spa/vanillajs#configure-auth0

## 動かし方

### 初回

```shell
cd <本リポジトリをcloneした場所>
npm ci
cp auth_config_template.json auth_config.json
# 自分の環境に応じた設定値を記入する
vim auth_config.json

npm start
# ブラウザでlocalhost:3000を開く
```

### 2回目以降

```shell
cd <本リポジトリをcloneした場所>
npm start
# ブラウザでlocalhost:3000を開く
```
