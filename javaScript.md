## Q1. What is the difference between var, let, and const in JavaScript?

var, let, and const are all used to declare variables in JavaScript. The main difference is their scope and mutability. var is function-scoped and allows both redeclaration and reassignment, which can lead to bugs. let is block-scoped, allows reassignment but not redeclaration. const is also block-scoped, but it cannot be reassigned after initialization. For objects and arrays declared with const, their properties or elements can still be modified. In modern JavaScript, it's recommended to use const by default and let only when reassignment is needed. var is generally avoided in modern code

## Q2. Explain the concept of hoisting in JavaScript.

Hoisting is JavaScript's behavior of moving declarations to the top of their scope before execution. Variables declared with var are hoisted and initialized with undefined, so accessing them before declaration returns undefined. Variables declared with let and const are also hoisted, but they remain in the Temporal Dead Zone until their declaration is reached, so accessing them earlier throws a ReferenceError. Function declarations are fully hoisted and can be called before they are defined, while function expressions are not.

```
Example 1: var

console.log(name); // undefined
var name = "Nur";
console.log(name); // Nur

Example 2: let

console.log(age); // ReferenceError: Cannot access 'age' before initialization
let age = 24;

Example 3: const

console.log(PI); // ReferenceError
const PI = 3.1416;

Example 4: Function Declaration

sayHello(); // Hello

function sayHello() {
    console.log("Hello");
}

Example 5: Function Expression

sayHello(); // ReferenceError

const sayHello = function () {
    console.log("Hello");
};
```

Q3. What are the primitive data types in JavaScript?
Q4. What is the difference between == and === in JavaScript?
Q5. Explain how closures work in JavaScript with an example.
Q6. What is the difference between null and undefined?
Q7. What are arrow functions and how do they differ from regular functions?
Q8. What is the scope chain in JavaScript?
Q9. Explain the concept of the temporal dead zone.
Q10. What is a pure function? Give an example.
Q11. What is the difference between function declaration and function expression?
Q12. What are default parameters in JavaScript?
Q13. What is the typeof operator and what are its possible return values?
Q14. Explain type coercion in JavaScript with examples.
Q15. What is an immediately invoked function expression (IIFE)?
