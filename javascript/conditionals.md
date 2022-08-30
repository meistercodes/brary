# Conditionals

## The if Statement

Use the if statement to specifiy a block of JavaScript code to be executed if a condition is true.

```js
if (number === 21) {
  console.log('Blackjack!');
}
```

## The else Statement

Use to specify a block of code to be executed if the condition is false.

```js
if (number === 21) {
  console.log('Blackjack!');
} else {
  console.log('Would you like another card?');
}
```

## The else if Statement

Use to specify a new condition if the first condition is false.

```js
if (number === 21) {
  console.log('Blackjack!');
} else if (number > 21) {
  console.log('Bust!');
} else {
  console.log('Would you like another card?');
}
```
