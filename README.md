Hello


*https://www.codewars.com/kata/simple-multiplication/train/javascript
```javascript
function simpleMultiplication(n) {
if (n%2 === 0){
 return n * 8;
 }else{
 return n * 9;
  }
}
```
* https://www.codewars.com/kata/students-final-grade/train/javascript
```javascript
function finalGrade (e, p) {
 if (e > 90 || p > 10) {
 return 100;
 }
 if (e > 75 && p >= 5){
 return 90;
 }
 if (e > 50 && p >= 2){
 return 75;
 }else{
 return 0;
 }
}
```
```javascript
* https://www.codewars.com/kata/type-of-sum/train/javascript
function typeOfSum(a, b) {
 let c = a + b;
 return typeof( c );
}
```
* https://www.codewars.com/kata/sleigh-authentication/train/javascript
```javascript
function Sleigh() {}

Sleigh.prototype.authenticate = function(name, password) {
  return name === 'Santa Claus' && password === 'Ho Ho Ho!';
};
```
==============
*New Solution
```javascript
function noSpace(x){
return x.replace(/ /g, '');
}
```javascript
function averageString(str) {
  let dict = ['zero', 'one', 'two', 'three', 'four', 'five', 'six', 'seven', 'eight', 'nine'];
  let arr = str.split(' ');
  let sum = 0;

  for (let i = 0; i < arr.length; i++){
   if (dict.includes(arr[i])){
   sum += dict.indexOf(arr[i]);
   }else{
   return 'n/a';
   }
   }
  let avg = Math.floor(sum/arr.length);
  return dict[avg];
}
```
*https://www.codewars.com/kata/sum-of-array-averages/train/javascript
const sumAverage = (arr) => {
  let result = 0;
  for (let i = 0; i < arr.length; i++){
  let sum = 0;
   for (let j = 0; j < arr[i].length; j++){
    sum += arr[i][j];
    }
    result = result + sum/arr[i].length;
   }
  return Math.floor(result);
}
***
const sumAverage = (arr) => {
  return Math.floor(arr.map(el => el.reduce((a,b) => a+b, 0)/el.length).reduce((a,b) => a+b, 0));
  }
  ```
*https://www.codewars.com/kata/number-of-people-in-the-bus/train/javascript
var number = function(busStops){
 return  busStops.reduce((sum, [a, b]) => (sum + a - b), 0);
}
```
*https://www.codewars.com/kata/convert-number-to-reversed-array-of-digits/train/javascript
function digitize(n) {
  let arr = n.toString().split("").reverse();
  let nArr = [];
  for (let i = 0; i < arr.length; i++){
  let a = Number(arr[i]);
    nArr.push(a);
  }
return nArr;
}
```
