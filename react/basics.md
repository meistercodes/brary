# React Basics

```js
ReactDOM.render(<p>Hello, World!</p>, document.getElementById('div'));
```

Is similar as:

```js
element = document.createElement('h1');
element.textContent = 'Hello World';
document.getElementById('div').appendChild(element);
```
