1. 
for (let i = 1; i <= 100; i++) {
  console.log(i);
}
2.
for (let i = 100; i >= 1; i--) {
  console.log(i);
}
3.
for (let i = 2; i <= 100; i += 2) {
  console.log(i);
}
4.
let arr = [];
for (let i = 0; i < 10; i++) {
  arr.push("x");
}
console.log(arr);
5.
let arr = [];
for (let i = 1; i <= 10; i++) {
  arr.push(i);
}
console.log(arr);
6.
let arr = [85,34,12,8,3];
for (let i = 0; i < arr.length; i++) {
  if (arr[i] > 0 && arr[i] < 10) {
    console.log(arr[i]);
  }
}
7.
let arr = [56,4,6,7,12];
let number2 = false;
for (let i = 0; i < arr.length; i++) {
  if (arr[i] === 5) {
    number2 = true;
  }
}
console.log(number2);
8.
let arr = [9,43,765,89];
let sum = 0;
for (let i = 0; i < arr.length; i++) {
  sum += arr[i];
}
console.log(sum);
9.
let arr = [3,5,6];
let sum = 0;
for (let i = 0; i < arr.length; i++) {
  sum += arr[i] ** 2;
}
console.log(sum);
10.
let arr = [2, 5, 9, 1, 4];
let sum = 0;
for (let i = 0; i < arr.length; i++) {
  sum += arr[i];
}
let mar = sum / arr.length;
console.log(mar);
