There are many number of methods can used with array in javascript most are below :
[lindked link](https://www.linkedin.com/feed/update/urn:li:activity:7287340230175596544/?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7287340230175596544%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29)


# Inshort

1. push()
2. pop()
3. shift()
4. unshift()
5. slice()
6. splice()
7. map()
8. filter()
9. reduce()
10. forEach()
11. find()
12. findIndex()
13. includes()
14. sort()



1. .push() 

what it does: Adds elements to the end of an array

use case : when you need to expand your array

let numbers = ["1,2"];
numbers.push("3");
console.log(numbers);


2. .pop()

what it does: Removes the last element and returns it

use case: When you want to remove or process the last item/elemnt

let numbers = [1,2,3];
let lastNumber = numbers.pop();
console.log(numbers);
console.log(lastNumber);


3. .shift()

what it does :Removes the first element and return it

use case:When you need to dequeue or process first elemnt

let numbers = [1,2,3,4];
let firstNumber = numbers.shift();
console.log(numbers);
console.log(firstNumber);


4. .unshift()

what it does :adds elements to the beginning of an array

use case: when you want to prepend items

let numbers = [3,4,5];
numbers.unshift(1,2);
console.log(numbers);


5. .slice()

what it does :returns a shallow copy of a portion of abn array without modifiying the original

use case:When you need a subset of an array

let  numbers = [1,2,3,4,5,6];
let sliced = numbers.slice(1,3);
console.log(sliced);
console.log(numbers);



6. .splice()

what it does : Adds,removes,or replaces lelments in an array

use case: when you need to modify the array directly

let numbers = [1,2,3,4,5];
numbers.splice(1,1,0); // replace



7. .map()

what it does :Transform every element in an array and returns an new array

use case: when you want to apply the same function to each item

let numbers = [1,2,3,4,5];
let plus2 = numbers.map(number => number + 2);
console.log(plus2);


8. .filter()

what it does: filter the array based on a condition and returns a new array

use case: when you want only specific items

let numbers = [1,2,3,4,5,6];
let evenNumbers = numbers.filter(number => number%2 == 0);
console.log(evenNumbers);




9. .reduce()

what it does: Reduce the array to a single value by applying a callback function

use case: when you need to summary value (e.g concatenation)

let numbers = [1,2,3,4,5,6];
let sumOfNumbers = numbers.reduce((acc,number) => acc + number,"")




10. .forEach()

what it does: executes the provides function once for each array element

use case: when you need to iterate through an array but don't need a new array

let numbers = [1,2,3,4,5];
numbers.forEach(numbere => console.log(number));



11.  .find()

what it does: Returns the first element that satisfies a condition

use case:When you are looking for specific item

let numbers =[1,2,3,4,5];
let firstEvenNumber = numbers.find(number => number === 2);
console.log(firstEvenNumber);


12. findIndex()

what it does : Return the index of the first element that satisfies a condition 

use case : when you need the position of an item

let numbers = [1,2,3,4,5];
let index = numbers.findIndex(number => number === 3);
console.log(index);


13. .includes()

what it does: checks if an array includes a certain value

use case: when you want to verify the exisitence of an item ( return boolen value);

let numbers = [1,2,3,4,5];
console.log(numbers.includes(3)); // true

console.log(numbers.includes(9));//false


14. .sort()

what it does : sort the elements of an array in place

use case: when you need a sorted array

let numbers = [3,1,4,2];
numbers.sort();
console.log(numbers);

// same for let characeters = ['b','c','d]'