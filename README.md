# abcde

마크다운도 쓸줄 모른다. 메모장 용도로 쓰면서 시작

맘대로 만들어둔 폴더를 vscode로 들어가서 npx creeate-react-app 원하는 파일명(나의경우 board)를 치면 만들어줌

기본 세팅을 뭐 해야하는것 같은데 
https://nomadcoders.co/react-for-beginners

그냥 이거 따라 한번 하고 만들기 시작하는게 좋은듯 하다. 포맷하고 다시 시작하고 싶네 뭐 이상하걸 너무 많이 받았어..

알아서 만들어 지는 src파일에서 App.js / App.css / index.js / index.css만 남기고 삭제함


App.js에서 초기 코드 정리는 아래와 같음
'''
import './App.css';

function App() {
  return (
    <div className="App">
    </div>
  );
}

export default App;
'''


index.js에서 초기 코드 정리는 아래와 같음
'''
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
import App from './App';

ReactDOM.render();
root.render(
    <App />,
  document.getElementById('root')
);
'''
