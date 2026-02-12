# JavaScript Learning Path - Building Gravitrips 🚀

## About Gravitrips
We'll build a simple gravity-based game where objects fall and you need to catch or avoid them!

---

## Task 1: Hello JavaScript! ⭐
**Goal:** Run your first JavaScript code

**What to do:**
1. Open `task1.html` in your browser
2. Open the browser console (Right-click → Inspect → Console tab)
3. You should see "Hello, Gravitrips!"

**Concepts learned:**
- `console.log()` - prints messages to the console
- How to connect JavaScript to HTML
- How to use browser developer tools

---

## Task 2: Variables and Data Types 📦
**Goal:** Store and use information

**Your challenge:**
In `task2.html`, create variables for:
- Player name (text/string)
- Player score (number)
- Game is active (true/false - boolean)

Print them all to the console.

**Example:**
```javascript
let playerName = "Alex";
let score = 0;
let isGameActive = true;
console.log(playerName, score, isGameActive);
```

**Concepts:**
- `let` - creates a variable that can change
- `const` - creates a variable that cannot change
- String (text), Number, Boolean (true/false)

---

## Task 3: Functions - Your First Tools 🔧
**Goal:** Create reusable code blocks

**Your challenge:**
Create a function called `startGame()` that:
- Prints "Game Started!"
- Sets score to 0
- Returns true

**Example structure:**
```javascript
function functionName() {
    // code here
    return something;
}
```

**Concepts:**
- Functions are reusable blocks of code
- `return` sends a value back
- Functions help organize your code

---

## Task 4: Making Decisions with If/Else 🤔
**Goal:** Make your code smart

**Your challenge:**
Create a function `checkScore(score)` that:
- If score > 100: print "You're a champion!"
- If score > 50: print "Great job!"
- Otherwise: print "Keep trying!"

**Example:**
```javascript
if (condition) {
    // do this
} else if (anotherCondition) {
    // do this instead
} else {
    // do this if nothing else matched
}
```

---

## Task 5: Arrays - Lists of Things 📋
**Goal:** Store multiple items

**Your challenge:**
Create an array of falling objects: ["star", "coin", "bomb"]
- Print the entire array
- Print just the first item
- Add a new item "gem" to the array
- Print the array length

**Concepts:**
- Arrays store lists: `let items = [1, 2, 3]`
- Access items: `items[0]` (first item)
- Add items: `items.push("new")`
- Get length: `items.length`

---

## Task 6: Loops - Do Things Repeatedly 🔄
**Goal:** Process multiple items

**Your challenge:**
Loop through your falling objects array and print each one with:
"Falling: [object name]"

**Two ways to loop:**
```javascript
// Method 1: for loop
for (let i = 0; i < array.length; i++) {
    console.log(array[i]);
}

// Method 2: forEach (easier!)
array.forEach(item => {
    console.log(item);
});
```

---

## Task 7: Objects - Group Related Data 🎮
**Goal:** Store complex information together

**Your challenge:**
Create a player object with:
- name
- score
- lives
- position (x and y coordinates)

Then print the player's name and position.

**Example:**
```javascript
let player = {
    name: "Alex",
    score: 0,
    position: { x: 100, y: 200 }
};
console.log(player.name);
console.log(player.position.x);
```

---

## Task 8: DOM Manipulation - Control the Webpage 🎨
**Goal:** Change HTML with JavaScript

**Your challenge:**
- Create a button in HTML
- When clicked, change a text paragraph
- Update a score display

**Key concepts:**
```javascript
// Find elements
document.getElementById("myId")
document.querySelector(".myClass")

// Change content
element.textContent = "New text";

// Listen for clicks
button.addEventListener("click", function() {
    // do something
});
```

---

## Task 9: Simple Animation ✨
**Goal:** Make things move!

**Your challenge:**
Create a falling object (a div) that:
- Starts at the top
- Moves down slowly
- Uses `setInterval()` to update position

**Concepts:**
```javascript
// Run code repeatedly
setInterval(function() {
    // this runs every 100ms
}, 100);

// Change CSS properties
element.style.top = "50px";
```

---

## Task 10: Build Gravitrips Prototype! 🎮
**Goal:** Combine everything you learned

**Features to implement:**
1. Create a game area (div)
2. Create a player (div) you can move left/right
3. Create falling objects that appear randomly
4. Detect when player catches an object
5. Keep score
6. Add a start button

**Bonus challenges:**
- Add sound effects
- Different object types (good vs bad)
- Increasing difficulty over time
- High score system

---

## Next Steps After Completing Tasks

Once you finish these tasks, you can:
1. Add more game features (power-ups, levels)
2. Improve graphics with CSS animations
3. Learn about game physics
4. Add touch controls for mobile
5. Save high scores using localStorage

**Resources:**
- MDN Web Docs: developer.mozilla.org
- JavaScript.info: javascript.info
- Practice on: codepen.io

Good luck! Take your time with each task and experiment! 🚀
