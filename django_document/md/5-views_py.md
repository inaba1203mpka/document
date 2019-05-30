# views.py
ここではsystem/views.pyについて説明する．  
views.pyは画面表示する為のデータを管理するファイルである．

## テンプレートビュー
参考ページ 
- [テンプレートビューのパターン](https://qiita.com/ytyng/items/7cb3c3a5605974151678)  
- [汎用ビューの使い方](https://qiita.com/felyce/items/7d0187485cad4418c073)

関数

- form_valid  
  フォームに値を入れたり，内容チェックなどの処理．
- get_context_date  
  models.pyからモデルを持ってきて，そのデータを表示するための関数
- get_query_set 
  models.pyから持ってきたデータの順番を操作する．

## TOPページ
try以下はtopページのカレンダーに予約時間を表示する為に，予約時間を整形する為の処理である．

## ログイン系
ログイン処理．  
クラスの引数にLoginRequireMixinが含まれるクラスはログイン中でないと見れないページである．

## 予約系
メールの処理は[これ](https://narito.ninja/blog/detail/64/)を参考
## 施設検索
