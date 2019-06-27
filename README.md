Hello


.https://www.codewars.com/kata/simple-multiplication/train/javascript
```
function simpleMultiplication(n) {
if (n%2 === 0){
 return n * 8;
 }else{
 return n * 9;
  }
}

.https://www.codewars.com/kata/students-final-grade/train/javascript
```
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
.https://www.codewars.com/kata/type-of-sum/train/javascript
function typeOfSum(a, b) {
 let c = a + b;
 return typeof( c );
}
```
.https://www.codewars.com/kata/sleigh-authentication/train/javascript
function Sleigh() {}

Sleigh.prototype.authenticate = function(name, password) {
  return name === 'Santa Claus' && password === 'Ho Ho Ho!';
};