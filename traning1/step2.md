## Question 2
httpd-{version} ディレクトリで `./configure`スクリプトを実行し、makefileの作成を正常に完了させなさい。
- **Answer 2**と同じ画面が出るようにすること  
- 依存関係のエラーが発生した場合は、必要に応じて依存ライブラリをインストールすること
- インストール先(Install prefix)には `/usr/local/httpd` を指定すること

## Answer 2
```
〜
Server Version: 2.4.41
Install prefix: /usr/local/httpd
C compiler:     gcc
CFLAGS:          -g -O2 -pthread
CPPFLAGS:        -DLINUX -D_REENTRANT -D_GNU_SOURCE
LDFLAGS:
LIBS:
C preprocessor: gcc -E
```

## Hint
`apt-get, libpcre3-dev, prefix`
