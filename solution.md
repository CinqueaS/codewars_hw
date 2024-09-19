## Return Negative

```js
function makeNegative(num) {
  if (num > 0) {
    return num * -1
  } else {
    return num
  }
}

makeNegative(42)
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  for (i = 0; i < arr.length; i++){
    if (arr[i] > 0){
      sum = arr[i] + sum 
    }
  } return sum
}
positiveSum(1,-2,3,4,5)
```

## Function 2

```js
function square(num1){
  return num1 ** 2
}
square(5)
```

## Sum Arrays

```js
function sum (numbers) {
    let x = 0
  for (i = 0; i < numbers.length; i++){
      x = numbers[i] + x 
  }return x
      
};
```

## Reversed Strings

```js
function solution(str){
  let reversedString = ""
  for (char of str)  {

        reversedString = char + reversedString;

  } return reversedString
}
solution("world")
```
