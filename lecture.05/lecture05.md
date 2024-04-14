# 第５回課題

## 課題内容:EC2にRailsアプリケーションをデプロイして構成図を作成しよう
- nginx+unicornでブラウザプレビュー
![nginx+unicornでブラウザプレビュー](./image/Nginx+unicorn.png)

- ALB追加
![ALB追加](./image/lecture05-ALB.png)
![ALB追加2](./image/lecture05-ALB-status.png)

- S3追加
![S3バケット](./image/lecture05-s3a-backet-list.png)
![S3バケットオブジェクト](./image/lecture05-s3a-backet-object.png)

- EC2→S3アクセスしてオブジェクト確認
![EC2→S3アクセスしてオブジェクト確認](./image/EC2→S3.png)

- ALB+S3追加後ブラウザプレビュー
![ALB+S3追加後ブラウザプレビュー](./image/ALB+S3.png)

- 構成図
![構成図](./image/lecture05.png)


### 感想
- nginx+unicornでの起動時にnginxがunicorn.sockを読み取りにいけないエラーの解決にとても時間がかかってしまった。そもそもファイルの読み取り事態に権限が必要だということがわかっていなかった。読み取り権限付与により解決できました。
- 今回の課題でログを追いかけることを沢山して、トラブル時はログを辿りエラー解消に向けたアクションが取れることが必要だと感じた。
