# コントローラー作成時に、定義できるアクション

## アクション名:役割
- new:データの新規作成フォームを表示する
- create:データを追加（保存）する
- index:データの一覧を表示する
- show:データの内容（詳細）を表示する
- edit:データを更新するためのフォームを表示する
- update:データを更新する
- destroy:データを削除する<br>

### ex)rails g controller Books new index show edit
### ex)rails g controller Review_tags create destroy(レビューとタグの間の中間テーブル)
