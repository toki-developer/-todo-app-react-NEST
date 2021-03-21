React + Nest.js で Todo アプリ(Nest.js)

React のリポジトリ
https://github.com/tokio-k/todo-app-REACT-nest

その他

- TypeORM
- sqlite
- class-validator

データ全件呼び出し
http://localhost:3000/item

データ 1 件検索
http://localhost:3000/item/{id}

データ新規追加
http://localhost:3000/item -X POST -d "todo={todo}&limit={limit}"

データ更新
http://localhost:3000/item/2/update -X PUT -d "todo={todo}&limit={limit}"

データ削除
http://localhost:3000/item/1/delete -X DELETE
