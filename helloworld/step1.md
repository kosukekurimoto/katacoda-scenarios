## Question 1
httpd をインストールするために必要な3つのファイル「httpd-2.4.41.tar.gz / apr-1.7.0.tar.gz / apr-util-1.6.1.tar.gz」を下記のWebサイトからダウンロードし、**Answer 1**と同じディレクトリ構成になるように配置しなさい

`https://httpd.apache.org/`{{copy}}
`https://apr.apache.org/download.cgi`{{copy}}

## Answer 1
```
httpd-2.4.41
├── 〜
├── 〜
└── srclib/
    ├── apr/
    └── apr-util/
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

## Index.json

In the file index.json we need to specify all the messages we will send from in the environment, for example:


<pre class="file">
"events": {
  "hideprogressbar": "reload-finished"
>>>>>>> master
}
</pre>

This is an example of Katacoda's clipboard integration. 

The following will copy the text into the clipboard. This is useful if users need to interactive with a web UI.

`docker`{{copy}}

Within the Markdown step, you would write:
<pre>
`docker`{{copy}}
</pre>

Katacoda supports copying code snippets or longer text into the clipboard by adding the attribute `data-target`.

<pre class="file" data-target="clipboard">
Copy Me To The Clipboard!!
</pre>

This is created by embedded HTML into the Markdown.

<pre>
&#x3C;pre class=&#x22;file&#x22; data-target=&#x22;clipboard&#x22;&#x3E;
Copy Me To The Clipboard!!
&#x3C;/pre&#x3E;
</pre>

**Note** Without the class="file" it will not display the clipboard functionality. For example:

<pre data-target="clipboard">
Not a file
</pre>

This was created by the HTML:

<pre>
&#x3C;pre data-target=&#x22;clipboard&#x22;&#x3E;
Not a file
&#x3C;/pre&#x3E;
</pre>


## Interrupt

When the user has long running commands, such as a watch, it can be useful to ensure that this is stopped but the user runs the next command. 

<pre>`echo "Send Ctrl+C before running Terminal"`{{execute interrupt}}</pre>

`echo "Send Ctrl+C before running Terminal"`{{execute interrupt}}

## Keyboard Icons

This can also be helped by using Keyboard symbols to show users to use <kbd>Ctrl</kbd>+<kbd>C</kbd>

The Markdown is:
<pre>
&#x3C;kbd&#x3E;Ctrl&#x3C;/kbd&#x3E;+&#x3C;kbd&#x3E;C&#x3C;/kbd&#x3E;
</pre>

## Execute on different hosts 

When using the `terminal-terminal` layout and multiple hosts within the cluster, you can have commands executed on which host is required. This is used within our [Kubernetes scenarios](https://www.katacoda.com/courses/kubernetes/getting-started-with-kubeadm).

<pre>
`echo "Run in Terminal Host 1"`{{execute HOST1}}

`echo "Run in Terminal Host 2"`{{execute HOST2}}
</pre>

`echo "Run in Terminal Host 1"`{{execute HOST1}}

`echo "Run in Terminal Host 2"`{{execute HOST2}}

## Execute in different Terminal windows

When explaining complex systems, it can be useful to run commands in a separate terminal window. This can be run automatically by including the target Terminal number. 

If the terminal is not open, it will launch and the command will be executed. 

<pre>
`echo "Run in Terminal 1"`{{execute T1}}

`echo "Open and Execute in Terminal 2"`{{execute T2}}

</pre>

`echo "Run in Terminal 1"`{{execute T1}}

`echo "Open and Execute in Terminal 2"`{{execute T2}}