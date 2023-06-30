#　非同期通信(Ajax:エイジャックス:Asynchronous JavaScript + XML)
<br>
## 非同期通信とは<br>
送信者のデータ送信タイミングと受信者のデータ受信タイミングを合わせずに通信を行う通信方式<br>
<br>
## 書き方<br>
- <%= form_with ~ local:true do |f| %><% end %>の、local:trueを外す<br>
-  また、remote: trueを付けることでも非同期通信が可能<br>
<br>
## 注意<br>
非同期通信になった状態でrender :indexとすると、index.html.erbではなく、index.js.erbを探しに行く<br>
(例えば、favorites_controllerのcreateアクションなら、app/views/favorites/create.js.erbが必要)<br>
