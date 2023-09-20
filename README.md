# Lesson 1.3 - Functions Review

Welcome to the recap of our lesson on JavaScript functions! This README is your handy reference guide. Whenever you need a quick refresher, pop in here.

## 1. **What is a Function?**
- A function in JavaScript is a block of reusable code that performs a specific task. 
- Functions are like recipes: they take inputs, process them, and return an output.

```javascript
function functionName(parameters) {
  // Body of the function
}
```

## 2. **Function Anatomy**
- **Function Name:** A unique name to identify and call the function.
- **Parameters (optional):** Inputs you provide to a function. They're placed inside parentheses.
- **Function Body:** Enclosed by `{}`. This is where the magic happens; it contains statements that define what the function does.

```javascript
function greet(name) {
  console.log("Hello, " + name);
}
```

## 3. **Calling a Function**
- To execute a function, you call it by its name followed by parentheses.

```javascript
greet("Alice");  // Outputs: Hello, Alice
```

## 4. **Parameters & Arguments**
- **Parameters:** Are names listed in the function definition. They are placeholders.
- **Arguments:** Are the real values passed to the function when you call it.

```javascript
function multiply(x, y) {
  return x * y;
}

multiply(2, 3);  // Here, 2 and 3 are arguments.
```

## 5. **Why Use Functions?**
- **Avoid Repetition:** Reusable pieces of code mean you don't have to rewrite the same logic.
- **Organize Code:** Makes code cleaner, more readable, and maintainable.
- **Modularity:** Break down complex problems into smaller, manageable chunks.

## 6. **Example: Without vs. With Functions**

```javascript
// WITHOUT Functions
let name1 = "Matt";
console.log("hi " + name1 + ", how are you");

let name2 = "Joe";
console.log("hi " + name2 + ", how are you");

// WITH Functions
function sayHello(name){
  console.log("hi " + name + ", how are you");
}

sayHello("Matt");
sayHello("Joe");
```

## 7. **Event Handlers**
- Special functions that respond to user interactions/events, making web pages interactive.

```javascript
let button = document.querySelector("button");
button.addEventListener('click', function() {
  alert('Button was clicked!');
});
```

## 8. **Key Takeaways**
- Functions are fundamental in JavaScript for organizing and reusing code.
- They can take inputs (parameters) and return outputs.
- Event handlers are functions that respond to user actions.

Happy coding!