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
