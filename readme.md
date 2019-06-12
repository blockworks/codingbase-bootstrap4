# bootstrapコーディングメモ

## 編集するSCSSファイル

* /scss/bootstrap.custom.scss　を編集、css/bootstrap.custom.cssをhtmlで読み込み。

## bootstrapの基本設定を触りたい場合

* /scss/bootstrap.custom.scss　の、@importより前に変更情報を記述する。
* 個別のスタイルもすべてここに記載。

## 注意事項

* SCSSコンパイルは、Preprosを使用。
* SCSSをコンパイルすると、「bootstrap.css」も生成されるが、使っていないので捨てても可。bootstrapをバージョンアップする時の事を考慮して、「bootstrap.scss/bootstrap.css」は残してあるだけ。
