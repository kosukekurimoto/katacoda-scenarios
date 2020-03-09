## Question 1
httpd をインストールする為には、下記の3つのパッケージが必要になる  
- httpd-{version}.tar.gz
- apr-{version}.tar.gz  
- apr-util-{version}.tar.gz  

下記のWebサイトから、それぞれ最新バージョンをダウンロードし **Answer 1** と同じディレクトリ構成になるように配置しなさい  
`https://httpd.apache.org/`{{copy}}  
`https://apr.apache.org/download.cgi`{{copy}}  

※{version} にはそれぞれのパッケージのバージョン番号が入る  

## Answer 1
```
httpd-{version}
├── 〜
├── 〜
└── srclib/
    ├── apr/
    └── apr-util/
```

## Hint
`wget, mv, tar`
