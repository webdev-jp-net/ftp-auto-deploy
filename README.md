# ftp-auto-deploy

[<img alt="Deployed with FTP Deploy Action" src="https://img.shields.io/badge/Deployed With-FTP DEPLOY ACTION-%3CCOLOR%3E?style=for-the-badge&color=0077b6">](https://github.com/SamKirkland/FTP-Deploy-Action)

[FTP Deploy](https://github.com/marketplace/actions/ftp-deploy) を設定して  
GitHub ActionsでFTPの自動デプロイを設定するサンプルです。

1. `release`ブランチへ`push`
2. 設定されたサーバへFTPで接続
3. gitリポジトリの`/htdocs`ディレクトリ配下のデータを、指定したサーバ上のリモートリポジトリへアップロード
