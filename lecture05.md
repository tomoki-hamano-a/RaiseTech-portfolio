# 第５回課題報告書
- nginx+unicornでブラウザプレビュー
![nginx+unicornでブラウザプレビュー](lecture.05/Nginx+unicorn.png)

- ALB追加
![ALB追加]((lecture.05/lecture05-ALB.png)
![ALB追加2](lecture.05/lecture05-ALB-status.png)

- S3追加
![S3バケット](lecture.05/lecture05-s3a-backet-list.png)
![S3バケットオブジェクト](lecture.05/lecture05-s3a-backet-object.png)

- EC2→S3アクセスしてオブジェクト確認
![EC2→S3アクセスしてオブジェクト確認](lecture.05/EC2→S3.png)

- ALB+S3追加後ブラウザプレビュー
![ALB+S3追加後ブラウザプレビュー](lecture.05/スクリーンショット 2023-09-13 185239.png)

- 構成図
![構成図](lecture.05/lecture05.png)


## 感想
- nginx+unicornでの起動時にnginxがunicorn.sockを読み取りにいけないエラーの解決にとても時間がかかってしまった。そもそもファイルの読み取り事態に権限が必要だということがわかっていなかった。読み取り権限付与により解決。
- 今回の課題でログを追いかけることを沢山して、トラブル時はログを辿りエラー解消に向けたアクションが取れることが必要だと感じた。
