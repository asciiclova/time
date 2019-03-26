古時刻スキル(Clova用のExtension)
====

## 本プログラムについて
本プログラムはLine Clova用スキルのExtensionプログラムのサンプルで
node.js言語で記述しています。

なお、本プログラムを実行するには、node.js(express)が実行できるWEBサーバが必要で
Clova Developper CenterからアクセスできるようURLが公開されている必要があります。

Clova Developper Centerについて詳しくはこちらをご参照ください
https://clova-developers.line.biz/

## Install　（AWS EC2の場合）
#### リポジトリの取得
`$ sudo curl -sL https://rpm.nodesource.com/setup_10.x | bash -`

#### nodejsのインストール

`$ sudo yum install -y nodejs`

#### ディレクトリ作成
`$ mkdir time`

#### ディレクトリ移動
`$ cd time`

#### 本プログラムをGIT Clone

`$ git clone git@github.com:asciiclova/time.git`

### Usage

ターミナルで、本ディレクトリtimeに入り、下記コマンドで実行

`$ node app.js`

Clova Developper Centerでスキルを作成して、動作テストを行うことができます。

## Licence

[MIT](https://github.com/ascii/tool/blob/master/LICENCE)

## Author

[ascii](https://github.com/ascii)
