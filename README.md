##環境構築

###Node.jsのインストール

#####Windows版
https://qiita.com/satoyan419/items/56e0b5f35912b9374305

#####Mac版
https://qiita.com/mii-chan/items/f3291ae8bbbf788c8aa3

Node.jsは11.0系で動作確認頭

次にcordova関連をインストール

#####cordova共通
$ npm install -g cordova
$ npm install -g phonegap
$ npm install -g ionic

#####プロジェクトの作成コマンド（CLI）
$ cordova create MyApp

#####プロジェクトに対応プラットフォームを追加する場合（カレントで行うこと）
$ cordova platform add browser
$ cordova platform add android
$ cordova platform add ios

#####ビルドし実行する場合
$ cordova run browser

#####参考文献
わかりやすいREADME.mdを書く
https://deeeet.com/writing/2014/07/31/readme/

CordovaをWindowsで。その1
https://qiita.com/567000/items/a36a742c45b2eb4a6a83

Cordova開発環境をつくる
https://cozyattic.wordpress.com/2016/12/26/cordova%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83%E3%82%92%E3%81%A4%E3%81%8F%E3%82%8B/

Android Studio
https://developer.android.com/studio/?hl=ja

