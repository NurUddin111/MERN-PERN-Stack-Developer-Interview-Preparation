# REACT QUESTIONS

## 01. What is React?

React is an open-source JavaScript library developed by Facebook for building fast, interactive, and reusable user interfaces, especially for single-page applications. It uses a component-based architecture, which allows developers to build reusable UI components. React also uses a Virtual DOM to efficiently update the user interface, improving performance and providing a better user experience.
Key Points
•	React is an open-source JavaScript library. 
•	Developed by Facebook (Meta). 
•	Used for building interactive user interfaces. 
•	Uses component-based architecture. 
•	Uses Virtual DOM for better performance.

## 02.	Why is React called a library instead of a framework?

React is called a library because it mainly focuses on building the user interface. It doesn't provide a complete solution for application development. For features like routing, state management, or API handling, developers choose additional libraries such as React Router, Redux, or Axios.
A framework, on the other hand, provides a complete structure and includes many built-in features. It usually controls how an application is organized, whereas React gives developers the flexibility to choose the tools they need.

## 03.	Can you give some examples of libraries used with React?

Yes. For example, React Router for routing, Redux or Zustand for state management, Axios for API requests, and React Query or TanStack Query for server state management.

## 04.	Is Next.js a framework?

Yes. Next.js is a React framework because it provides additional features like file-based routing, server-side rendering, API routes, image optimization, and many built-in capabilities.

## 05.	So, is React enough to build a complete application?

Yes, React can be used to build an application, but for most real-world projects, developers use additional libraries or a framework like Next.js to handle features such as routing, server-side rendering, and state management.

## 06.	Why do you use React instead of Vanilla JavaScript?

React is built on top of JavaScript, so it's not a replacement for JavaScript. We use React because it makes building complex and interactive user interfaces much easier.
React provides reusable components, efficient UI updates through the Virtual DOM, declarative programming, and a large ecosystem. These features make applications easier to develop, maintain, and scale compared to using only Vanilla JavaScript.
Key Points
•	React doesn't replace JavaScript. 
•	Makes UI development easier. 
•	Reusable Components. 
•	Virtual DOM. 
•	Declarative programming. 
•	Easier maintenance. 
•	Better scalability.

## 07.	Can we build websites using only Vanilla JavaScript?
Yes. We can build websites using only Vanilla JavaScript. However, as applications become larger and more interactive, managing the code becomes more difficult. React helps solve that problem by providing reusable components and better state management.

## 08.	When would you choose Vanilla JavaScript?
For small websites or simple projects, Vanilla JavaScript is often enough. For larger applications with many interactive features, React is usually a better choice because it's easier to maintain and scale.

## 09.	What is the Virtual DOM, and how does it improve performance?
The Virtual DOM is a lightweight copy of the Real DOM maintained by React. Whenever the application's state changes, React first updates the Virtual DOM instead of directly updating the Real DOM. It then compares the new Virtual DOM with the previous one, identifies only the changed elements, and updates only those parts in the Real DOM. This process is called reconciliation, and it improves performance by reducing unnecessary DOM updates.
Key Points
•	Virtual DOM = lightweight copy of the Real DOM. 
•	React updates the Virtual DOM first. 
•	React compares the old and new Virtual DOM. 
•	This comparison is called Reconciliation. 
•	Only the changed parts are updated in the Real DOM. 
•	Fewer DOM updates = better performance.

## 10.	What is Reconciliation?
Reconciliation is the process where React compares the previous Virtual DOM with the updated Virtual DOM to identify changes and efficiently update only the necessary parts of the Real DOM.

## 11.	What are Components? What are the different types of Components?
Components are the building blocks of a React application. A component is a reusable piece of UI that contains its own structure, logic, and styling. Instead of writing the same code multiple times, we create components and reuse them throughout the application.
There are two main types of components: Functional Components and Class Components. Today, Functional Components are the recommended approach because they are simpler, easier to read, and support React Hooks. Class Components were commonly used before Hooks were introduced but are now less common in modern React development.
Key Points
•	Components are building blocks of React. 
•	Components are reusable. 
•	Improve code organization. 
•	Improve maintainability. 
•	Two types: 
o	Functional Components ✅ 
o	Class Components 
•	Functional Components are preferred today because they support Hooks.
