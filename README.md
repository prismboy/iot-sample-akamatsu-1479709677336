# IoTサンプルプロジェクト

## プロジェクトの概要

　このプロジェクトには２つのIoTサンプルアプリケーションが稼動している。
１つはIBM Watson IoT Platformを使用したiPhoneネイティブアプリとWebアプリを接続するもの。
もう１つはWebブラウザからWatson IoT Platform QuickStarterを使用するもの。

ランタイムはBluemixのボイラープレート"Internet of Things Platform Starter"により作成されている。

　iPhone用ネイティブアプリはGithubで公開されている [iot-starter-for-ios](https://github.com/ibm-watson-iot/iot-starter-for-ios.git) より取得し、Xcodeにてビルドする。

スマートフォン用Webブラウザ版 [QuickStarter版](http://phonesensor.mybluemix.net) を起動してd:quickstart.phone-sensor:に表示されているIDをIoT出力ノードのDeviceIDに設定する。

Node-REDのフローはインデックスページより『サンプルアプリのフロー』からリンクされたJSONからフローエディタでimportする。

![IoT Quickstart](images/iot_quickstart.png)
