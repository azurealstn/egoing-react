# egoing-react

## App Render

### HTML 렌더링

```javascript
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App /> //App을 렌더링해준다.
  </React.StrictMode>
);
```

### CSS 불러오기

```javascript
import './App.css';
```

### Component

```javascript
function Header() { //함수형 컴포넌트
  return <header>
    <h1><a href='/'>WEB</a></h1>
  </header>
}
function Nav() { //함수형 컴포넌트
  return <nav>
    <ol>
      <li><a href='/read/1'>html</a></li>
      <li><a href='/read/2'>css</a></li>
      <li><a href='/read/3'>js</a></li>
    </ol>
  </nav>
}
function Article() { //함수형 컴포넌트
  return <article>
    <h2>Welcome</h2>
    Hello, WEB
  </article>
}
function App() {
  return (
    <div>
      <Header></Header> //헤더 컴포넌트 불러오기
      <Nav></Nav> //네비게이션 컴포넌트 불러오기
      <Article></Article> //아티클 컴포넌트 불러오기
    </div>
  );
}
```

## Read

### 💡Before

![read1](https://user-images.githubusercontent.com/55525868/226170366-4a41c482-db3b-4730-a614-d7f4f0fd5674.png)

### 🎇 After

![read2](https://user-images.githubusercontent.com/55525868/226170370-79541119-e3a6-44b3-a29d-81976bbb0ade.png)

## Create

### 💡Before

![create1](https://user-images.githubusercontent.com/55525868/226170374-f15384ff-03e8-4f02-8ea3-d8a7be6ef4eb.png)

### 🎇 After

![create2](https://user-images.githubusercontent.com/55525868/226170377-00c3cc70-79b4-490b-8db3-9b1bd0924800.png)

## Update

### 🎇 After

![update1](https://user-images.githubusercontent.com/55525868/226170380-d830455e-51c3-4c9f-ae47-22a09d904f82.png)

## Delete

### 💡Before

![delete1](https://user-images.githubusercontent.com/55525868/226170382-41829377-3fc8-401b-a66c-4e070ace1de4.png)

### 🎇 After

![delete2](https://user-images.githubusercontent.com/55525868/226170383-4515002a-fb83-4b8d-902d-a49247729269.png)