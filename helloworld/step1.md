# training1 - 静的 Webサーバー を構築する

## Goal
- Webサーバーを構築し、静的なコンテンツをWebブラウザから表示できる環境を構築する

# Apache HTTP Server(httpd) のインストール

## Question-1-1
httpd をインストールするために必要なファイルを、下記の3つのWebサイトからダウンロードし、Goal と同じディレクトリ構成になるように配置しなさい

`hint: wget, tar`

## Answer-1-1


```bash
wget https://downloads.apache.org//httpd/httpd-2.4.41.tar.gz
```

```
wget https://downloads.apache.org//apr/apr-1.7.0.tar.gz
```

```sh
wget https://downloads.apache.org//apr/apr-util-1.6.1.tar.gz
```