# git pullしたときに起きるコンフリクトに関するメモ

## git pullしたときに、エラーでpullできないとき
- git fetchで、一旦ローカルリポジトリへ取り込む(main以外のpullは、後ろにブランチ名が必要かも？）
- git statusで、「Unmerged paths:」に出てくるファイルを開き、変更点で正しい方を「use」にする
- git commitする
- コミットが完了すれば、マージされた状態になる
