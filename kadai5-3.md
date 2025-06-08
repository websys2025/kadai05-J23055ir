## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
  * エンドポイント：https://zipcloud.ibsnet.co.jp/api/search
  * 機能：郵便番号７桁から住所を検索することが出来る
* リクエストとレスポンスのフォーマット
  * リクエスト：GET
  * レスポンス：JSON
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
  * APIの名称：緯度経度API
  * 参照URL：https://maps.gsi.go.jp/development/ichiran.html
* エンドポイントと機能
  * エンドポイント；https://msearch.gsi.go.jp/address-search/AddressSearch
  * 機能：地名を入れると、その地名の緯度と経度が出力される
* リクエストとレスポンスのフォーマット
  * リクエスト：GET
  * レスポンス：JSON
### Q3-3. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* Web APIの利便性や課題など
  * 今回の外部APIの課題は中々結果が表示されず、encodeURIComponentによって日本語が適切なURLに変換されないと、そもそも自分が入力した地点を読み取ってもらえないことを知るまで苦労をした。
