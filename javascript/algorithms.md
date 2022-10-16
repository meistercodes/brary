# JavaScript Algorithms

## repeatString

Create a function that takes two arguments, the word and the amount of times for it to be copied (word, times). Return an ERROR if "times" is less than 0.

```js
function repeatString(word, times) {
  if (times < 0) return 'ERROR';
  const string = '';
  for (i = 0; i < times; i++) {
    string += word;
  }
  return string;
}
```

## reverseString

Create a function that takes in an argument (string) and reverses it.

```js
function reverseString(string) {
  return string.split('').reverse().join('');
}
```

## removeFromArray

Create a function that removes an item from an array. NOTE: use rest syntax!

```js
const removeFromArray = function (...args) {
  const array = args[0];
  const newArray = [];
  array.forEach((item) => {
    if (!args.includes(item)) {
      newArray.push(item);
    }
  });
  return newArray;
};
```
