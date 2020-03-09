## Question 3
httpd のコンパイルとインストールを正常に完了させ、httpdのバージョン確認コマンドを実行して、**Answer 3**と同じ内容が表示されることを確認しなさい

## Answer 3
```
$ /usr/local/httpd/bin/httpd -v
Server version: Apache/{インストールしたバージョン} (Unix)
Server built:   Mar  9 2020 15:53:55`
```

## Hint
`make`


Render port 8500: https://[[HOST_SUBDOMAIN]]-8500-[[KATACODA_HOST]].environments.katacoda.com/

Render port 80: https://[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com/

Display page allowing user to select port:
https://[[HOST_SUBDOMAIN]]-[[KATACODA_HOST]].environments.katacoda.com/