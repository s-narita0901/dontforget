#### 備忘録です
  * .mdはとても便利らしい
  * githubの使い方はネットで調べた  gitの使い方はドットインストールで確認できる

#### 環境構築について
  * python: `sudo apt-get python2.7`
  * idle: `sudo apt-get idle`

#### MongoDBについて  
  * 公開鍵の設定  
`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 7F0CEB10`

  * mongodb.listの作成  
`echo 'deb http://downloads-distro.mongodb.org/repo/ubuntu-upstart dist 10gen' | sudo tee /etc/apt/sources.list.d/mongodb.list`

  * apt-getのアップデート。  
`sudo apt-get update`

  * ○○をインストールする。  
`sudo apt-get ○○`

  * mongodbの開始、停止、再起動。  
`sudo service mongodb start`
`sudo service mongodb stop`
`sudo service mongodb restart`

#### githubのssh登録について
  * <http://monsat.hatenablog.com/entry/generating-ssh-keys-for-github>
