# Docker for WordPress.
これはDockerを使用したWordPressの環境構築のテンプレートになります。

# 開発環境の構築
1. .env_sampleファイルの名前を.envに変更し、WORDPRESSとMYSQLの情報を入力する。

2. 下記のコマンドをdocker-compose.ymlがあるディレクトリにて叩く。    
  docker-compose up -d

3. ローカルホストにアクセスし、WordPressの初期設定を行う。   
  http://localhost:8000/wp-admin/install.php 
  
# 開発環境の停止
  docker-compose down 
