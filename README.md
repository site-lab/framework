# framework
PHP、Pythonのフレームワークを紹介しています。
※自己責任で実行してください

## テスト環境
### conohaのVPS
* メモリ：512MB
* CPU：1コア
* SSD：20GB

### さくらのVPS
* メモリ：512MB
* CPU：1コア
* SSD：20GB

### さくらのクラウド
* メモリ：1GB
* CPU：1コア
* SSD：20GB

### IDCFクラウド
* メモリ：1GB
* CPU：1コア
* SSD：15GB

### 実行方法
SFTPなどでアップロードをして、rootユーザーもしくはsudo権限で実行
wgetを使用する場合は[環境構築スクリプトを公開してます](https://www.logw.jp/cloudserver/8886.html)を閲覧してください。
wgetがない場合は **yum -y install wget** でインストールしてください

**sh ファイル名.sh** ←同じ階層にある場合

**sh /home/ユーザー名/ファイル名.sh** ユーザー階層にある場合（rootユーザー実行時）

## 共通内容
* epelインストール
* gitのインストール
* システム更新
* LAMP構築+phpmyadmin
* HTTP2の有効化
* firewallのポート許可(80番、443番)
* gzip圧縮の設定
* centosユーザーの作成


HTTP2通信対応版となります。HTTP2通信を行う場合はこっちを使って下さい

## [apache24u_fuelphp73_mariadb103.sh](https://github.com/site-lab/framework/blob/master/apache24u_fuelphp73_mariadb103.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.x
* PHP7.3
* MariaDB10.3

HTTP2通信対応版となります。HTTP2通信を行う場合はこっちを使って下さい

## [apache24_fuelphp_mariadb103.sh](https://github.com/site-lab/framework/blob/master/apache24_fuelphp73_mariadb103.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.x
* MariaDB10.3

## [apache24_fuelphp_mariadb104.sh](https://github.com/site-lab/framework/blob/master/apache24_fuelphp73_mariadb104.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.x
* MariaDB10.4

## [apache24_fuelphp_mariadb105.sh](https://github.com/site-lab/framework/blob/master/apache24_fuelphp73_mariadb105.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.x
* MariaDB10.5


## [apache_fuelphp73_mysql57.sh](https://github.com/site-lab/framework/blob/master/apache_fuelphp73_mysql57.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.3
* MySQL5.7

## [apache_fuelphp73_mysql80.sh](https://github.com/site-lab/framework/blob/master/apache_fuelphp73_mysql80.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.3
* MySQL8.0



## [apache_fuelphp73_mariadb103.sh](https://github.com/site-lab/framework/blob/master/apache_fuelphp73_mariadb103.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.3
* MariaDB10.3


## [apache_laravel73_mariadb103.sh](https://github.com/site-lab/framework/blob/master/apache_laravel72_mariadb103.sh)
Laraveをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.3
* MariaDB10.3
