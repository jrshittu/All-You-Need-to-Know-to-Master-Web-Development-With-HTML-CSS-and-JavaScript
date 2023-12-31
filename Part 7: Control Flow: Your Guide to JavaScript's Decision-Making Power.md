## Conquering Control Flow: Your Guide to JavaScript's Decision-Making Power.

## Contents
[Introduction](#intro)
[Conditional Statements](#conditions)
[Loops](#loops)
[Break and Continue](#break)
[Projects](#pro)
[References and Resources](#ref)

**Unlocking Dynamic JavaScript with Control Flow**

Control flow is like a director, guiding your code through various paths and decisions. It's essential for building interactive and responsive programs that adapt to user input and changing conditions. Here's a guide to mastering control flow in JavaScript, packed with examples and use cases:

**Key Concepts and Examples**

**1. Conditional Statements:**
   - **if/else:**
      - **Example:** "If the user is logged in, display their profile. Else, show the login page."
      ```javascript
      if (isLoggedIn) {
        showProfile();
      } else {
        showLoginPage();
      }
      ```
   - **switch/case:**
      - **Example:** "Choose a language based on the user's selection."
      ```javascript
      switch (selectedLanguage) {
        case "en":
          setLanguage("English");
          break;
        case "es":
          setLanguage("Spanish");
          break;
        default:
          setLanguage("English"); // Default option
      }
      ```

**2. Loops:**
   - **for loop:**
      - **Example:** "Count down from 10 to 1, displaying each number."
      ```javascript
      for (let i = 10; i >= 1; i--) {
        console.log(i);
      }
      ```
   - **while loop:**
      - **Example:** "Repeat a quiz question until the user answers correctly."
      ```javascript
      while (answer !== correctAnswer) {
        askQuestion();
        answer = getUserInput();
      }
      ```
   - **for...of loop:**
      - **Example:** "Display each item in a shopping cart."
      ```javascript
      for (const item of cartItems) {
        console.log(item.name, item.price);
      }
      ```

**3. Break and Continue:**
   - **Break:**
      - **Example:** "Exit a loop when a specific condition is met."
      ```javascript
      for (let i = 0; i < 100; i++) {
        if (foundItem) {
          break; // Exit the loop when item is found
        }
        // Continue searching...
      }
      ```
   - **Continue:**
      - **Example:** "Skip to the next iteration of a loop."
      ```javascript
      for (let i = 0; i < numbers.length; i++) {
        if (numbers[i] % 2 === 0) {
          continue; // Skip even numbers
        }
        // Process odd numbers...
      }
      ```
## Projects <a name="pro"></a>
**Project 1: Coin Flipping Game**

```javascript
function playCoinGame() {
  let correctGuesses = 0;
  const totalFlips = 3; // Adjust for desired number of flips

  for (let i = 1; i <= totalFlips; i++) {
    const coinFlip = Math.random() >= 0.5 ? "heads" : "tails";
    console.log(`Flip ${i}: Guess heads or tails?`);

    let userGuess = "";
    while (userGuess !== "heads" && userGuess !== "tails") {
      userGuess = prompt("Enter your guess (heads or tails):").toLowerCase();
      if (userGuess !== "heads" && userGuess !== "tails") {
        console.log("Invalid guess. Please enter heads or tails.");
      }
    }

    if (userGuess === coinFlip) {
      console.log(`Correct! It's ${coinFlip}.`);
      correctGuesses++;
    } else {
      console.log(`Incorrect. It was ${coinFlip}.`);
    }
  }

  console.log(`You guessed ${correctGuesses} out of ${totalFlips} correctly.`);
}

playCoinGame();
```

**Project 2: Text-Based Adventure Game**

```javascript
let currentRoom = "start";

function startRoom() {
  console.log("You are in a dark forest.");
  console.log("There is a path to the north and a cave to the east.");
  let choice = prompt("Do you go north or east?");
  if (choice.toLowerCase() === "north") {
    currentRoom = "north";
  } else if (choice.toLowerCase() === "east") {
    currentRoom = "cave";
  } else {
    console.log("Invalid choice.");
    startRoom();
  }
}

// Add more rooms and choices as needed

startRoom();
```

**Project 3: Password Generator**

```javascript
function generatePassword(length, requirements) {
  let characters = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%^&*()_+-=[]{};':\"\\|,.<>/?";
  let password = "";

  for (let i = 0; i < length; i++) {
    let randomIndex = Math.floor(Math.random() * characters.length);
    let character = characters[randomIndex];

    // Check requirements (example)
    if (requirements.includes("uppercase") && !/[A-Z]/.test(password)) {
      character = character.toUpperCase();
    }

    password += character;
  }

  return password;
}

const password = generatePassword(12, ["uppercase", "number", "symbol"]);
console.log(password);
```

## References and Resources <a name="ref"></a>
**Official Documentation:**

* **MDN Web Docs:** [https://developer.mozilla.org/en-US/docs/Glossary/Control_flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)
* **JavaScript Guide:** [https://javascriptguide.com/](https://javascriptguide.com/)

**Tutorials and Articles:**

* **FreeCodeCamp:** [https://www.freecodecamp.org/news/full-javascript-course-for-beginners/](https://www.freecodecamp.org/news/full-javascript-course-for-beginners/)
* **W3Schools:** [https://www.w3schools.com/js/js_loop_for.asp](https://www.w3schools.com/js/js_loop_for.asp)
* **The Net Ninja:** [https://www.youtube.com/watch?v=JloLGV9DmtQ](https://www.youtube.com/watch?v=JloLGV9DmtQ)

**Books:**

* **Eloquent JavaScript:** [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
* **JavaScript for Kids:** [https://www.pdfdrive.com/javascript-for-kids-e18717703.html](https://www.pdfdrive.com/javascript-for-kids-e18717703.html)

**Videos:**

* **Khan Academy:** [https://en.wikipedia.org/wiki/Control_flow](https://en.wikipedia.org/wiki/Control_flow)
* **Traversy Media:** [https://www.youtube.com/watch?v=hdI2bqOjy3c](https://www.youtube.com/watch?v=hdI2bqOjy3c)
* **Coding with Chris:** [https://www.youtube.com/watch?v=zIJ1udbeoYY](https://www.youtube.com/watch?v=zIJ1udbeoYY)




