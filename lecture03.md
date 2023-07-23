# 第３回課題
- APサーバ名・バージョン:puma　・ver7.0.4
- APサーバーを終了させた場合、引き続きアクセスできるか:できない
- ![AP sever not running](/image/AP%20server%20not%20running.png)
- APサーバーを起動させた場合
- ![AP sever running](/image/AP%20server%20running.png)
- DBサーバー名・バージョン:mysql　・ver8.0.34
- DBサーバーを終了させた場合、引き続きアクセスできるか:できない
- ![DB server not running](/image/DB%20server%20not%20running.png)
- Railsの構成管理ツールの名前:bundler

## レポート
- アプリはAPサーバー、データベースはDBサーバーとそれぞれ分業されていること、どちらかが欠けてもアクセスは失敗することがわかりました。APサーバーがブラウザとの連携によるWEB処理までしてくれるのは助かると感じました。
