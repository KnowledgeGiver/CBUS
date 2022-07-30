The past 2 weeks we've learned about several programming fundamentals. These fundamentals will allow you to create any program you want. But you do need practice in order to learn how to piece everything together. So we're going to focus on a larger lab in order to do so. Essentially reviewing everything we've done. There are going to be some exercises that we've seen before, some that are familiar, and some that are entirely new.

Variables are like the building blocks of our programming languages. It is where information is stored that we could later use. But there is extra information that we have to be conscious of in order to use them effectively.
## All about variables and data types

### Exercise - Variable creation
Explain how to create variables.
- What are the three keywords that you could use in order to create a variable?
- When do you use each of the keywords?
- What are their similarities?
- What are their differences?

### Exercise - Primitive types
Create a variable for each _primitive_ data type that exists in JavaScript (Except bigint and Symbol).

Under each variable explain the primitive data type. And when or why you would use the data type of the variable.

### Exercise - Variable reassignment
Now that you created variables. Reassign 2 of them.

### Exercise - Booleans
By just looking at the following expressions, determine in your mind whether or not each will evaluate to true or false. After you made your guess. Test each result by using `console.log`

- `999 > 999`
- `999 == 999`
- `999 != 999`
- `-5 >= -4`
- `100 <= -100`
- `20 + 5 < 5`
- `81 / 9 == 9`
- `9 != 8 + 1`

Using the provided variable definitions, replace the blanks (underscores) with a mathematical or boolean operator that evaluates the expression to true (some may have more than one right answer, just choose one)

Test your answers by using `console.log` for each expression in your answer file.
```javascript
const a = 4;
const b = 53;
const c = 57;
const d = 16;
const e = 'Kelvin';
const f = false;

a _ b
c _ d
'Name' _ 'Name'
a _ b _ c
a _ a _ d
e _ 'Kevin'
48 _ '48'
f _ e
```
### Exercise - String methods
Strings are a very special primitive data type. The reason they're special is because they are the first data type which introduces _methods_ to the mix. The effective creation, usage, modification, and even deletion of strings is very important to programming as most information will be a string.

Here are some major string methods. Pick any 3 and research what they do and how to use them. Make sure to type up some examples of usage in your code. And run your files!!!

> Note: some of these are going to be used in later exercises... ;)

- `.charAt()`
- `.concat()`
- `.includes()`
- `.indexOf()`
- `.slice()`
- `.split()`
- `.substring()`
- `.toLowerCase()`
- `.toUpperCase()`
- `.trim()`

### Exercise - Strings, concatenating, and variables
Create 2 variables.
1. One variable with your full name
2. One variable with your favorite food

Use these variables to `console.log` the phrase "Hello. My name is \_\_\_\_ and my favorite food is \_\_\_\_."

Do this using both...
1. string concatenation
2. template literals

### Exercise - null and undefined
Explain what `null` and `undefined` represent. And when each of those values may appear in your code.

### Exercise - Array methods
Arrays aren't a primitive data type but they are still highly important to understand how to create more complex programs. When you get information from a database, such as a list of active users, they will all be returned in an array.

Here are some major array methods. Pick any 3 and research what they do and how to use them. Make sure to type up some examples of usage in your code. And run your files!!!

> Note: some of these are going to be used in later exercises... ;)

- `.concat()`
- `.filter()`
- `.find()`
- `.forEach()`
- `.includes()`
- `.indexOf()`
- `.join()`
- `.map()`
- `.pop()`
- `.push()`
- `.reverse()`
- `.shift()`
- `.slice()`
- `.sort()`
- `.splice()`
- `.unshift()`

## Control Flow
Control flow is how you redirect your code logic to different parts of your program. How you take certain actions when certain criteria is met.

There are a few major ways to control flow in your programs
- if statements
- if/else statements
- if/else if/else statements
- loops
  - for loops
  - while loops
  - A few other loops we didn't learn in class (yet)

### Exercise - Loops and conditionals
- Create a loop that will print "hi" 15 times.
- Create a loop that will print "YEP!" 30 times.
- Loop through an array (use both a _for_ loop and a _while_ loop)
  - Loop from left to right
  - Loop from right to left
- Create a loop that logs the EVEN numbers from 98-0 (descending)
- Create a loop that logs the numbers from 3-90 that are multiples of 3 (ascending)
- Create a while loop that'll iterate from both ends of the array at the same time. And meets in the middle. When it meets in the middle stop the loop.
- Fizzbuzz
  - Create a loop. That counts from 1-100. When you have a number divisible by 3 `console.log` "Fizz". When you have a number divisible by 5 `console.log` "Buzz". When you have a number divisible by both 5 and 3 `console.log` "FizzBuzz"
- Create a conditional that will output the grade of a student according to this image


![Letter Grade](https://i.imgur.com/4PUhOZy.png)