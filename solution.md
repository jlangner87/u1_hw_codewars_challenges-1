## Return Negative

```js
function makeNegative(num) {
  return num * -1
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      sum += arr[i]
    }
  }
  return sum
}
```

## Function 2

```js
const square = (num) => {
  return num * num
}
```

## Sum Arrays

```js
function sum(numbers) {
  'use strict'
  let sumNum = 0
  if (numbers.length > 0) {
    for (let i = 0; i < numbers.length; i++) {
      sumNum += numbers[i]
    }
    return sumNum
  } else if (numbers.length === 0) {
    return 0
  }
}
```

## Reversed Strings

```js
function solution(str) {
  let revStr = ''
  for (let i = str.length - 1; i >= 0; i--) {
    revStr += str[i]
  }
  return revStr
}

//I did not think that would work!!! I didnt know if .length worked on strings, but I searched it on W3, and it exists!
```
