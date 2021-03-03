# Single Page Application - Todo Trello 

## Tech Stack 🚀
* Vanilla Javascript
* Sass
* async await API

## Tree 🚀
```
├── App.js
    ├── TodoInput.js
    ├── Users.js
    ├── Loading.js
    └── Trello.js
        └── TodoList.js
```

## TodoApp에 API 연동 🚀
* API를 통해 다른 user의 todolist를 불러올 수 있습니다.  
* 할 일을 추가할 수 있습니다.
* 할 일을 삭제할 수 있습니다.
* 선택된 user의 할 일을 모두 삭제할 수 있습니다. ( 다른사람 list 손대지 않기 )
* 할 일 완료여부를 토글할 수 있습니다.

## 구현된 기능 🚀
* Loading page : `delay=` 코드를 사용하여 로딩 중임을 사용자에게 알리는 처리 및 오작동하지 않게 하는 로딩 페이지를 처리를 했습니다.
  * svg 를 사용하여 유동적으로 보여지는 ui를 나타냅니다.

* Mini Trello
  * `Trello.js` 에 해야할 일, 완료된 일 두개의 `TodoList.js` 인스턴스가 존재합니다.
  * 완료된 항목과 그렇지 않은 항목을 **Drag & Drop** 으로 옮길 수 있습니다.

