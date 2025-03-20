## Answer 1
let numbers = [1, 2, 3, 4, 5];

numbers.forEach(function(num) {
    console.log(num);
});

## Answer 2
let words = ["apple", "banana", "cherry"];

words.forEach(function(word) {
    console.log(word.length);
});

## Answer 3
let numbers = [1, 2, 3, 4, 5, 6];

numbers.forEach(function evenNumbers(num) {
    if (num % 2 == 0) {
        console.log(num);
    } else {
        return evenNumbers;
    }
});

## Answer 4
let health = 50;

if (health >= 10 < 50) {
    console.log("not terrible");
} else if (health =< 0) {
    console.log("terrible");
} else if (health >= 50) {
    console.log("optimal");
}

## Answer 5
["t", "r", "u", "s", "t"] 
The letter "t" has been indexed to the first letter in the array which was "c"

## Answer 6
let array1 = [1, 2, 3];
let array2 = ["a", "b", "c"];

if (array1.length == array2.length) {
    print true;
} else {
    print false;
}

## Answer 7
halves = 2
weeks = 2

## Answer 8
let strings = ["First", "Second", "Third"];
let finalString = "";

strings.forEach(function(str) {
    finalString = finalString + str;
});
console.log(finalString);

## Answer 9
isOld = true;
isYoung = false;
isAlive = true;
isConfusing = false;

## Answer 10
<h1 class="underline" id="headline">What is JavaScript?</h1>
<p class="underline">JavaScript is a programming language.</p>

let headlineElement = document.getElementById("headline");