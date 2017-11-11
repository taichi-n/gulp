# gulp利用手順

まずは、gulpを利用するプロジェクトのルートディレクトリに移動しておく。

## nodeの確認

```
node --version
v6.3.1 
```
nodeが入ってることを確認。

## package.jsonの作成

```
npm init
```
と打つと、package.jsonというnpmの設定ファイルが作成。
このファイルに、このあとインストールしていくモジュールの名称やバージョンが自動的に書き込まれていく。

## gulpのインストール
ローカルのgulpを動かすために？グローバルにもインストールする必要があるらしい

```
npm i -g gulp
```
この処理の後、
```
npm i --save-dev gulp
```
としてローカルにもインストール。

このときに、このとき、terminal上に
```
npm WARN フォルダ名 No description
npm WARN フォルダ名 No repository field.
npm WARN フォルダ名 No README data
npm WARN フォルダ名 No license field.
```
とか出るかもしれないけど一旦無視。

