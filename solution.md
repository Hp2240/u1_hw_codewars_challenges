## Return Negative

```js
function makeNegative(num) {
  return num * -1
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let result = 0

  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      result += arr[i]
    }
  }
  return result
}
```

## Function 2

```js
function square(num) {
  return Math.pow(num, 2)
}
```

## Sum Arrays

```js
function sum(numbers) {
  let sum = 0
  ;('use strict')
  for (let i = 0; i < numbers.length; i++) {
    if (numbers[i] !== 0) {
      sum += numbers[i]
    }
  }
  return sum
}
```

## Reversed Strings

```js
function solution(str) {
  let arr = []
  let reversedStr = ''

  for (let i = 0; i < str.length; i++) {
    arr.push(str[i])
  }
  arr.reverse()
  for (let i = 0; i < str.length; i++) {
    reversedStr = reversedStr + arr[i]
  }
  return reversedStr
}
```
