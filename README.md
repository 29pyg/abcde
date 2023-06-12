# abcde

마크다운도 쓸줄 모른다. 메모장 용도로 쓰면서 시작

기본 세팅을 뭐 해야하는것 같은데 

그냥 이거 따라 한번 하고 만들기 시작하는게 좋은듯 하다. 포맷하고 다시 시작하고 싶네 뭐 이상하걸 너무 많이 받았어..
https://nomadcoders.co/react-for-beginners

여기에서 #5의 Introduction에서 폴더명?짓는거 부터 천천히 배운다.

npx create-react-app board 맨 마지막의 board가 폴더명이다. 

터미널에서 vscode로 실행하려면 code board(폴더명)을 한다. 근데 또 저렇게 하면 npm start할때 경로에서 오류나더라

그럴땐 경로를 cmd 창에다 code (경로) 하고 붙여서 경로 오류는 해결했다.

내 경로 C:\Windows\System32/projects/board




알아서 만들어 지는 src파일에서 App.js / App.css / index.js / index.css만 남기고 삭제함


**App.js에서 초기 코드 정리는 아래와 같음**
```
import './App.css';

function App() {
  return (
    <div className="App">
    </div>
  );
}

export default App;
```



**index.js에서 초기 코드 정리는 아래와 같음**
```
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
import App from './App';

ReactDOM.render();
root.render(
    <App />,
  document.getElementById('root')
);
```


**html파일의 경우 !Tab을 누르면 자동으로 아래의 코드가 작성된다**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
