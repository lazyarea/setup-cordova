#### Cordovaのドキュメント
    http://qiita.com/Itomaki/items/2eb7b69f1d8a42101963
    http://cordova.apache.org/docs/en/5.0.0/guide/platforms/index.html#Platform%20Guides

#### Cordovaのインストール
    $ npm install -g cordova

#### Create the App
    $ cordova create hello com.example.hello HelloWorld
    create はサブコマンド名
    hello はディレクトリ
    com.example.hello はアプリ識別子（逆ドメイン表現）
    HelloWorld はアプリのディスプレイのタイトル

#### Add Plarform
    $ cd hello
    $ cordova platform add android
    $ cordova platforms ls

#### Build the App of Android
    $ cordova build android

#### Emulate on Real Device
    $ cordova emulate

#### Emulate on Emulator
    $ cordova emulate android
