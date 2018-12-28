# docker-for-wp
これはDockerを使用したWordPressの環境構築のテストになります。

# 開発環境の構築

1. 下記のコマンドをdocker-compose.ymlがあるディレクトリにて叩く。    
  docker-compose up -d

2. ローカルホストにアクセスし、WordPressの初期設定を行う。   
  http://localhost:8000/wp-admin/install.php 
  
# 開発環境の停止
  docker-compose down 
