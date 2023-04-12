# Getting Started with Create React App
### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

---
state, dispatch, nextId를 위한 context를 만들어서 상태관리

APP -> TodoHead, TodoList, TodoCreate

TodoList -> todo -> TodoItem

Context -> todos -> TodoHead, TodoList
        -> dispatch -> TodoItem, TodoCreate
