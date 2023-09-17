# Assignment-4-Javascript-Problem-Solving-Raw
// 💎 Problem number-1 💎
/* 
📝 Description: This function can do multiple operations like addition, subtraction, multiplication, and division for a positive number at a time. 
*/
function mindGame(num) {
  if (typeof num === 'number') {
    if (num >= 0) {
      let result = (num * 3 + 10) / 2 - 5;
      return result;
    } else {
      return "You are giving a negative number";
    }
  } else {
    return "It is not a valid input";
  }
}

// 💎 Problem number-2 💎
/*
📝 Description: This is a function that shows the sum of characters in a string as odd or even.
*/
function evenOdd(str) {
  if (typeof str === "string") {
    if (str.length % 2 == 0) {
      let result = "even";
      return result;
    } else {
      let result1 = "odd";
      return result1;
    }
  } else {
    return "It is not a valid input";
  }
}

// 💎 Problem number-3 💎
/*
📝 In this function, we are going to find the difference between the input value and 7.
*/
function isLGSeven(input) {
  let result = input - 7;
  if (result < 7) {
    return result;
  } else if (result >= 7) {
    let newResult = input2;
    return newResult;
  }
}

// 💎 Problem number-4 💎
/*
📝 In this function, we are going to find out bad data from an array.
*/
function findingBadData(arr) {
  let sum = 0;
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] < 0) {
      sum += 1;
    }
  }
  return sum;
}

// 💎 Problem number-5 💎
/*
📝 This is a function of three input numbers then you can convert those numbers into one number by running some problematic operation.
*/
function gemsToDiamond(num1, num2, num3) {
  let total = num1 * 21 + num2 * 32 + num3 * 43;
  
  if (total >= 2000) {
    return total - 2000;
  } else {
    return total;
  }
}

