# Assignment-4-Javascript-Problem-Solving-Raw
// Problem number-1
/* description: This function can do multiple operation like addition, Subtraction, Multiplication and division for a positive number at a time.
*/
function mindGame(num){
if(typeof num === 'number'){
if(num >=0){
let result = (num * 3 + 10) / 2 - 5;
return result;
}
else {
return "you are giving a negative number" ;
}
}
else {
return "It is not a valid input";
}
}
// problem number--2
/* description: This is a function that shows the sum of characters in a string as odd or even */
function evenOdd(str){
if(typeof str=== "string") {
if ( str.length %2 ==0 ){
let result = "even" ;
return result;
}
else {
let result1 ="odd";
return result1;
}
}
else {
return "It is not a valid input";
}
}
// problem number--3
/* In this function we are going to find the difference between the input value and 7 */
function isLGSeven( input){
let result= input-7;
if(result<7 ){
return result;
}
else if (result>=7){
let newResult=input*2;
return newResult;
}
}
// problem number--4
/* in this function we are going to find out bad data from an array */
function findingBadData(arr) {
let sum = 0;
for (let i = 0; i < arr.length; i++) {
if (arr[i] < 0) {
sum += 1;
}
}
return sum;
}
// problem number-5
/* This is function of three input number then you can covert those number into one number by running some problematic operation */
function gemsToDiamond(num1, num2, num3) {
let total = num1 * 21 + num2 * 32 + num3 * 43;
if (total >= 2000) {
return total - 2000;
} else {
return total;
}
}
