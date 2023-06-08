# コントローラー作成時に、定義できるアクション
<br>
## アクション名:役割<br>
- new:データの新規作成フォームを表示する<br>
- create:データを追加（保存）する<br>
- index:データの一覧を表示する<br>
- show:データの内容（詳細）を表示する<br>
- edit:データを更新するためのフォームを表示する<br>
- update:データを更新する<br>
- destroy:データを削除する<br>
<br>
### ex)rails g controller Books new index show edit<br>
### ex)rails g controller Review_tags create destroy(レビューとタグの間の中間テーブル)
