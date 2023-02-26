---
id: hello-world
title: Hello World
permalink: docs/hello-world.html
prev: release-channels.html
next: introducing-jsx.html
---

The smallest React example looks like this:

```jsx
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<h1>Hello, world!</h1>);
```

It displays a heading saying "Hello, world!" on the page.

**[Try it on CodePen](https://codepen.io/gaearon/pen/rrpgNB?editors=1010)**

Click the link above to open an online editor. Feel free to make some changes, and see how they affect the output. Most pages in this guide will have editable examples like this one.


## How to Read This Guide {#how-to-read-this-guide}

In this guide, we will examine the building blocks of React apps: elements and components. Once you master them, you can create complex apps from small reusable pieces.

>Tip
>
>This guide is designed for people who prefer **learning concepts step by step**. If you prefer to learn by doing, check out our [practical tutorial](/tutorial/tutorial.html). You might find this guide and the tutorial complementary to each other.

This is the first chapter in a step-by-step guide about main React concepts. You can find a list of all its chapters in the navigation sidebar. If you're reading this from a mobile device, you can access the navigation by pressing the button in the bottom right corner of your screen.

Every chapter in this guide builds on the knowledge introduced in earlier chapters. **You can learn most of React by reading the “Main Concepts” guide chapters in the order they appear in the sidebar.** For example, [“Introducing JSX”](/docs/introducing-jsx.html) is the next chapter after this one.

## Knowledge Level Assumptions {#knowledge-level-assumptions}

React is a JavaScript library, and so we'll assume you have a basic understanding of the JavaScript language. **If you don't feel very confident, we recommend [going through a JavaScript tutorial](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) to check your knowledge level** and enable you to follow along this guide without getting lost. It might take you between 30 minutes and an hour, but as a result you won't have to feel like you're learning both React and JavaScript at the same time.

## At least learn below concepts of javascript before react
To learn React, you will need to have a good understanding of the following JavaScript concepts and technologies:

JavaScript Fundamentals: You should have a good grasp of the basics of JavaScript, including variables, data types, functions, objects, and control flow. This will help you understand how React works and how to write clean and effective React code.

ES6 and Beyond: React uses many features of the latest versions of JavaScript, including arrow functions, classes, and modules. You should be familiar with these concepts to be able to write modern React code.

Functional Programming: React is a functional programming library, and it heavily uses concepts like immutability, pure functions, and higher-order functions. Having a solid understanding of these concepts will help you write more efficient and maintainable React code.

Asynchronous Programming: React applications often make use of asynchronous programming techniques, such as promises and async/await. You should understand how to work with asynchronous data to be able to build complex React applications.

HTML and CSS: Although React is mainly focused on JavaScript, it is still important to have a good understanding of HTML and CSS. React components are usually rendered to the DOM, and knowing how to style and structure HTML and CSS will be beneficial.

Node.js and npm: React applications are usually built with Node.js and use npm (Node Package Manager) to manage dependencies. It is important to understand how to work with Node.js and npm to build and manage React applications.

>Note
>
>This guide occasionally uses some newer JavaScript syntax in the examples. If you haven't worked with JavaScript in the last few years, [these three points](https://gist.github.com/gaearon/683e676101005de0add59e8bb345340c) should get you most of the way.


## Let's Get Started! {#lets-get-started}

Keep scrolling down, and you'll find the link to the [next chapter of this guide](/docs/introducing-jsx.html) right before the website footer.


