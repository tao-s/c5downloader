# c5downloader

One file downloader

concrete5の最新版をダウンロード、展開するスクリプトです。
concrete5をインストールしたいディレクトリにc5downloader.phpをアップロードし、ブラウザでアクセスしてください。
zipの展開、ファイルの移動など、面倒くさいところはexec()でシェルコマンド実行してるので、exec()が使えないサーバでは使えませんが試してみたら主なレンタルサーバで使えました。

## 使えたレンタルサーバ

* ロリポップ
* heteml
* CPI
* さくらのレンタルサーバ スタンダード
* Windows Azure Website 
