# Switch Statement

Another type of a conditional statement

Example:

```js
const grade = 87;

switch (true) {
  // If score is 90 or greater
  case grade >= 90:
    console.log('B');
    break;
  // If score is less than 90
  case grade < 90:
    console.log('Keep Studying');
    break;
  // If neither of the above conditions are true
  default:
    console.log("You don't have a grade");
}
```
