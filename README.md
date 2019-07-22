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
*https://www.codewars.com/kata/numerical-palindrome-number-5-1/train/javascript
function palindrome(num) {
  if (typeof num !== 'number' || num < 0){
  return 'Not valid';
  }
  if (num < 10) return false;
num = num.toString().split('').sort();
 console.log(num);
 let count = 0;
 for(let i = 0; i < num.length - 1; i){
  if (num[i] === num[i+1]){
  count = count + 2;
  i = i + 2;
  }else{
  i++
  }
 }
 if(num.length === count || num.length === count + 1){
 return true;
 }else{
 return false;
 }
}
```
*https://www.codewars.com/kata/maximum-triplet-sum-array-series-number-7/train/javascript
function maxTriSum(numbers){
 let sum = 0;
 let arr = [];
 let res = numbers.sort((a,b) => b - a);
 for(let i = 0; i < res.length; i++){
 if(arr.length === 3){
  break;
  }
 if(!arr.includes(res[i])){
   arr.push(res[i]);
   sum += res[i];
   }
 }
 return sum;
}
```
*https://www.codewars.com/kata/print-a-rectangle-using-asterisks/train/javascript
function getRectangleString(w, h) {
  const rn = '\r\n';
  const tb = '*'.repeat(w) + rn;
  const center = (w > 1) ? ('*' + ' '.repeat(w-2) + '*' + rn).repeat(h-2) : '';
  return h > 1 ? (tb + center + tb) : tb.repeat(h);

}
```
*https://www.codewars.com/kata/convert-to-binary/train/javascript
function toBinary(n){
  return +n.toString(2);
}
```

