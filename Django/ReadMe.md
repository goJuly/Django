 # ReadMe 

 ## 概要
 
「動かして学ぶ！Python　Django　開発入門」の内容を、Docker及びコンテナ上のMySQLを利用して実現したものです。

## インストール
 1. python -m venv 環境名を実施
 2. pip install wheel
 3. pip install django
 4. pip install mysqlclient
 5. https://startbootstrap.com/themes/one-page-wonder/
 
 ## 詰まったこととか。
 
 1. pip install mysqlclientを実施したときに、C++ がないと怒られるので、vs_buildtoolsをインストール。
 2. pip install mysqlclientを実施したときに、pythonが32bitだと怒られるので、64bitにバージョンアップ。
 3. DockerDesktopで、HEIDISQLを接続する際には、127.17.0.1がポート。Django　setting.pyでは、127.0.0.1がポートとなる。
  