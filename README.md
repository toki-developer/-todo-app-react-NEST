### About

React + Nest.js で Todo アプリ(Nest.js)

React のリポジトリ

https://github.com/tokio-k/todo-app-REACT-nest

### Clone and Run the App

Clone the app:

```
git clone git@github.com:tokio-k/-todo-app-react-NEST.git
cd -todo-app-react-NEST
```

Install dependencies:

```
yarn
```

Run the app:

```
yarn start
```

http://localhost:3000

その他

- TypeORM
- sqlite
- class-validator

* データ全件呼び出し
  http://localhost:3000/item

* データ新規追加
  http://localhost:3000/item

-X POST -d "todo={todo}&limit={limit}"

- データ更新
  http://localhost:3000/item/{id}/update

-X PUT -d "todo={todo}&limit={limit}&isDone={isDone}"

- データ削除
  http://localhost:3000/item/{id}/delete

-X DELETE
