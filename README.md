React + Nest.js でTodoアプリ(Nest.js)

Reactのリポジトリ
https://github.com/tokio-k/todo-app-REACT-nest

その他
* TypeORM
* sqlite
* class-validator

データ全件呼び出し
http://localhost:3000/item

データ新規追加
http://localhost:3000/item -X POST -d "todo=〇〇 limit=〇〇〇〇-〇〇-〇〇"

データ更新
http://localhost:3000/item/2/update -X PUT -d "todo=〇〇 limit=〇〇〇〇-〇〇-〇〇"

データ削除
http://localhost:3000/item/1/delete -X DELETE