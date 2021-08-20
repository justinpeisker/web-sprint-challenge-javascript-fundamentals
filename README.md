# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

        .map()- .map is an array method that allows you to convert the data of an array without changing the original array.  .map will return a new array and requires a return keyword.  .map would be quite useful if you needed to change certain case values (upper or lower) to the data in an array.
        
        .reduce()- .reduce is an array method that will return a single value.  This method is usually used for addition or multiplication, but doesn't have to be.  .reduce will not change the original array.  This method would be useful if you needed the sum of the populations of multiple cities in an array.

        .filter()- .filter is an array method that allows you to filter the data and return the results to a new array.  It is useful if you needed to find cities that had a population greater than or less than a given number.

2. Explain the difference between a callback and a higher order function.

        A higher order function is a function that receives a function (a callback function) as an argument.  A callback function is a function that is used as an argument in a higher order function.   

3. Explain what a closure is.

        A closure happens when a nested function reaches outside of itself and into the outer function to grab data.

4. Describe the four principles of the 'this' keyword.

        The four principles of the 'this' keyword are window binding, implicit binding, explicit binding, and new binding.  Window binding will apply if none of the other binding principles apply.  Window binding means the 'this' keyword is bound to the window or global object.  If you are operating in 'strict mode' it will retrun undefined.  Window binding for the this keyword is bad practice and one of the other three binding principles should be used.  Implicit binding is the most common type of binding.  When a function is invoked, implicit binding says whatever is left of the '.' is what the 'this' keyword is bound to.  Explicit binding occurs when we explicitly indicate what 'this' is refering to using .apply, .call, or . bind.  New binding occurs when we use the 'new' keyword construct a new object. The 'this' keyword is bound to the newly created object when the function is invoked as a constructor function.

5. Why do we need super() in an extended class?

        super() calls the attributes of the parent class.  It replaces the .call command when using class syntax.  The 'this' keyword will now be bound to the parent attributes, as well as any attributes explicity stated in the child class.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

