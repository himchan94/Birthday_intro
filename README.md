## 프로젝트 정리

<h3>페이지가 리렌더링될 때</h3>
<ul>
  <li>자신의 상태(state)가 변경될 때</li>
<li>부모 컴포넌트가 리렌더링될 때/li>
<li>자신이 전달받은 props가 변경될 때/li>
<li>forceUpdate 함수가 실행될 때/li>
  </u1>
  
  
  <h3>코드분석</h3>
  data.js에서 받아온 데이터를  App.js에서 받아온다.
  받아온 데이터들은 const [people, setPeople] = useState(data)를 통해 state 값으로 지정하고
  list 컴포넌트에 이 state 값들을 props 넘겨준다.
  
  
