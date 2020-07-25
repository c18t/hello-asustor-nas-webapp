# hello-asustor-nas-webapp

hello-asustor-nas-webapp は Web アプリ用 ASUSTOR アプリケーションパッケージファイル作成の練習です。

## 使い方

以下のコマンドでパッケージファイルを作成します。

```console
$ python2 ./APKG_Utilities_2.0/apkg-tools.py create ./src
```

ASUSTOR NAS の管理画面にログインし、App Central を開きます。

管理の手動インストールタブからパッケージをインストールします。

デスクトップに hello-asustor-nas-webapp のアイコンが作成されるので、クリックして Hello World ページを表示します。

## 参考

- [ASUSTOR Developer Corner / Tools](https://developer.asustor.com/)
  - App Central Developer Guide
  - App Build Tools
  - Sample Custom apk
