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
```
*https://www.codewars.com/kata/filter-coffee/train/javascript
function search(budget, prices) {
return prices.filter((el) => el <= budget).sort((a, b) => a-b).join();


}
```
*https://www.codewars.com/kata/merge-two-sorted-arrays-into-one/train/javascript
function mergeArrays(arr1, arr2) {
let newArr = [];
for (i = 0; i < arr1.length; i++){
 if (!newArr.includes(arr1[i])){
  newArr.push(arr1[i]);
  }
 }
for (i = 0; i < arr2.length; i++){
 if (!newArr.includes(arr2[i])){
  newArr.push(arr2[i]);
  }
 }
 return newArr.sort((a,b) => a-b);
}
```
