# remote_container_template
リモートコンテナ用テンプレートリポジトリ

## ディレクトリ名の変更

ルートディレクトリ名を変えたい場合は以下を変更すること。

https://github.com/TakedaTakumi/remote_container_template/blob/862f64ca86ec2234b6788a96d9963cb61326e776/.devcontainer/devcontainer.json#L18-L20
https://github.com/TakedaTakumi/remote_container_template/blob/862f64ca86ec2234b6788a96d9963cb61326e776/.devcontainer/docker-compose.yml#L23-L25

`workspace` を任意の名前に変更する。  
※同じ名前にする必要がある。

## 拡張機能の変更

下記を修正する。
追加したい場合は、拡張機能のIDを配列に追加して、リモートコンテナをRebuildする。
https://github.com/TakedaTakumi/remote_container_template/blob/862f64ca86ec2234b6788a96d9963cb61326e776/.devcontainer/devcontainer.json#L25-L39
