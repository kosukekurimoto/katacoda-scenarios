## Apache HTTP Server(httpd) のインストール

## Question 1-1
httpd をインストールするために必要なファイルを、下記の3つのWebサイトからダウンロードし`Answer 1-1`と同じディレクトリ構成になるように配置しなさい

`hint: wget, tar`

## Answer 1-1
```

```


```bash
wget https://downloads.apache.org//httpd/httpd-2.4.41.tar.gz
```

```
wget https://downloads.apache.org//apr/apr-1.7.0.tar.gz
```

```sh
wget https://downloads.apache.org//apr/apr-util-1.6.1.tar.gz
```

<<<<<<< HEAD
## Index.json

In the file index.json we need to specify all the messages we will send from in the environment, for example:

<pre class="file">
"actions": {
  "hideprogressbar": {}
=======
## Mapping event in index.json

In the file index.json the message received in the EventService should be mapped to which event we want to raise, for example:

<pre class="file">
"events": {
  "hideprogressbar": "reload-finished"
>>>>>>> master
}
</pre>