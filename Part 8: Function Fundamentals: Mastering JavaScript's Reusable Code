## Function Fundamentals: Mastering JavaScript's Reusable Code

## Contents
[Introduction](#intro)
[Defining Functions](#def)
[Calling Functions](#call)
[Passing Arguments](#pass)
[Best Practices](#best)
[Projects](#pro)
[References & Resources](#ref)

![Let's go gif](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gsw4fjikno2i728dqpgn.gif) <a name="intro"></a>
Imagine writing the same code repeatedly in your JavaScript program. Tedious, right? That's where functions come in! They're the reusable blocks of code that save you time and make your programs cleaner and more efficient. This concise guide will equip you with everything you need to know about defining, calling, and passing arguments to functions in JavaScript.

**Defining Functions:**<a name="def"></a>

* Use the `function` keyword followed by a name and parentheses:
  ```javascript
  function sayHello(name) {
    console.log("Hello, " + name + "!");
  }
  ```
* You can specify arguments enclosed in the parentheses.
* The function body contains the code to be executed.

**Calling Functions:** <a name="call"></a>

* Use the function name followed by parentheses:
  ```javascript
  sayHello("John"); // Outputs: "Hello, John!"
  ```
* You can pass arguments inside the parentheses when calling the function.

**Passing Arguments:** <a name="pass"></a>

* Arguments are like variables that receive values when the function is called:
  ```javascript
  function addNumbers(x, y) {
    return x + y;
  }

  let result = addNumbers(5, 10); // result will be 15
  ```
* The number of arguments passed should match the function's definition.

**Best Practices:** <a name="best"></a>

* Choose meaningful function names that describe their purpose.
* Use comments to explain what the function does and its arguments.
* Avoid too many arguments; keep functions focused and modular.
* Consider returning values from functions for flexibility.
* Practice writing different types of functions to solidify your understanding.

## Projects <a name="pro"></a>
**Project 1: Rock, Paper, Scissors Game**

```javascript
function playRockPaperScissors() {
  const userChoice = prompt("Choose rock, paper, or scissors:").toLowerCase();
  const computerChoice = ["rock", "paper", "scissors"][Math.floor(Math.random() * 3)];

  function determineWinner(user, computer) {
    if (user === computer) {
      return "It's a tie!";
    } else if ((user === "rock" && computer === "scissors") ||
               (user === "paper" && computer === "rock") ||
               (user === "scissors" && computer === "paper")) {
      return "You win!";
    } else {
      return "Computer wins!";
    }
  }

  const result = determineWinner(userChoice, computerChoice);
  console.log(`You chose ${userChoice}, computer chose ${computerChoice}. ${result}`);
}

playRockPaperScissors();
```

**Project 2: Simple Calculator**

```javascript
function add(x, y) {
  return x + y;
}

function subtract(x, y) {
  return x - y;
}

function multiply(x, y) {
  return x * y;
}

function divide(x, y) {
  if (y === 0) {
    return "Cannot divide by zero";
  } else {
    return x / y;
  }
}

let operation = prompt("Choose an operation (+, -, *, /):");
let num1 = parseFloat(prompt("Enter the first number:"));
let num2 = parseFloat(prompt("Enter the second number:"));

let result;
switch (operation) {
  case "+":
    result = add(num1, num2);
    break;
  case "-":
    result = subtract(num1, num2);
    break;
  case "*":
    result = multiply(num1, num2);
    break;
  case "/":
    result = divide(num1, num2);
    break;
  default:
    console.log("Invalid operation");
    return;
}

console.log(`The result is: ${result}`);
```

**Project 3: Password Validator**

```javascript
function validatePassword(password) {
  const requirements = {
    minLength: 8,
    uppercase: /[A-Z]/,
    lowercase: /[a-z]/,
    number: /[0-9]/,
    symbol: /[!@#$%^&*()_+-=[]{};':"\\|,.<>?]/
  };

  let isValid = true;
  for (const [requirement, regex] of Object.entries(requirements)) {
    if (!regex.test(password)) {
      console.log(`Password must include ${requirement}`);
      isValid = false;
    }
  }

  if (isValid) {
    console.log("Password is valid!");
  }
}

const userPassword = prompt("Enter a password to validate:");
validatePassword(userPassword);
```

**References:** <a name="ref"></a>
Check out MDN Web Docs for comprehensive documentation on JavaScript functions: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)

