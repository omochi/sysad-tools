# システム管理スクリプト

# 公開鍵操作

`.ssh/authorized_keys`を編集するコマンドがあります。

~~~
$ sysad-pubkey show
~~~

ユーザーの公開鍵のAAフィンガープリントを一覧表示します。
壊れた行や二重登録の検出もします。

~~~
$ sysad-pubkey add
~~~

公開鍵を追加します。
ファイルがまだ無い場合
二重登録を防止します。

~~~
$ sysad-pubkey delete
~~~

公開鍵を1つ削除します。



# インストール

~~~
$ sudo ./install
~~~

`/usr/local/sbin`にインストールされるので、
sudoersのsecure_pathに追加が必要です。




