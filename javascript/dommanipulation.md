# Working with the DOM

## Selecting Elements

```js
// Returns a reference to the first match of selector
document.querySelector('.container'); // Returns the first element with a class of 'container'

// Returns a reference to all of the selectors
document.querySelectorAll('.container'); // Returns all elements with a class of 'container'

// Returns the first ID with matching name
document.getElementById('container');
// Is the same as ...
document.querySelector('#container');
```
