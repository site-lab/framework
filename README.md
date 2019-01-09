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

## [apache_fuelphp72_mariadb103.sh](https://github.com/site-lab/framework/blob/master/apache_fuelphp72_mariadb103.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.2
* MariaDB10.3

## [apache_fuelphp72_mysql57.sh](https://github.com/site-lab/framework/blob/master/apache_fuelphp72_mysql57.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.2
* MySQL5.7



## [apache_fuelphp73_mariadb103.sh](https://github.com/site-lab/framework/blob/master/apache_fuelphp73_mariadb103.sh)
FuelPHPをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.3
* MariaDB10.3

## [apache_laravel72_mariadb103.sh](https://github.com/site-lab/framework/blob/master/apache_laravel72_mariadb103.sh)
Laraveをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.2
* MariaDB10.3

## [apache_laravel73_mariadb103.sh](https://github.com/site-lab/framework/blob/master/apache_laravel72_mariadb103.sh)
Laraveをインストールします。
PHP7は **モジュール版** となります
* apache2.4.6
* PHP7.3
* MariaDB10.3

## [nginx_laravel72_mariadb103_drn.sh](https://github.com/site-lab/framework/blob/master/nginx_laravel72_mariadb103_drn.sh)
Laraveをインストールします。
PHP7は **FastCGI版** となります
* nginx
* PHP7.2
* MariaDB10.3
