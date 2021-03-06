# FEW 2.3 - Lesson 1

Getting started with Single Page Applications and React. 

| **Elapsed** | **Time** | **Activity** |
| ----------- | --------- | ------------ |
| 0:05 | 0:05 | [Learning Objectives](#class-learning-objectives) |
| 0:05 | 0:10 | [Single Page Applications](#single-page-applications) |
| 0:10 | 0:20 | [Lecture](#lecture) |
| 1:30 | 1:50 | [Lab](#lab) |
| 0:10 | 2:00 | [Break](#break) |
| 0:30 | 2:30 | Review progress on Tutorial |
| 0:10 | 0:10 | Review Homework |
| 0:05 | 2:45 | Review objectives |

## Overview

### Learning Objectives

1. Create components
1. Use JSX 
1. Differentiate props and state 
1. Define the virtual DOM

## Single Page Applications

Single Page Applications (SPA) are web pages that act as software applications. A traditional web site is made up several pages all linked, where the current web page is removed from memory when a new page is loaded.  A Single Page Application is a single web page that loads data and displays different content by changing the content of the current page without loading a new web page.

The [Killer App](https://en.wikipedia.org/wiki/Killer_application) for SPAs was Gmail. Gmail is a single web page that lists your email, views email, sends email and more all within a single HTML document.

SPAs are the way web pages of more than minimal complexity are created these days. These days when you visit a web site you are loading a single HTML file that displays many different views that provide the experience of a fully interactive multipage site.

## Lecture

## Why Learn React

React is one of the most popular web frameworks available today and with good reason. It's fast efficient and has a great workflow and developer experience. 

React uses functional reactive programming to solve many of the headaches of creating user interfaces.

It's also popular with all of the big name companies. 

- Airbnb
- Facebook
- Instagram
- Netflix
- New York Times
- Yahoo! Mail
- Khan Academy
- Whatsapp
- Vivaldi Browser
- Codeacademy
- Dropbox
- Uber
- Twitter 
- Pinterest
- Instacart
- Reddit 
- Hubspot
- Disqus
- Pandora
- and many more...

If you are going to master a single framework make it this one! It's hugely popular and all of the top companies are using it. Expect to see React on job applications and in use at companies you might apply to. 

Beyond this React has moved frontend web development forward and laid the groundwork for modern front end systems. Expect future front end frameworks to build and evolve on what React has done. 

### What is React?

What does the React team have to say about React? 

> Pair up and read this: [https://reactjs.org](https://reactjs.org)

React describes itself as: 

> A JavaScript library for building user interfaces

React is used for building user interfaces. It's the view in any system. It's a little more but building UI is what React was made to do.

### Functional Programming

React is built on Functional Reactive programming. In a nutshell, functional programming is programming with functions. FP avoids mutable data and shared state. 

### Reactive Programming

In a nutshell, Reactive programming is programming with Event Streams. 

An Event Stream is like an Array of events. Arrays map things in space. Event streams map things in time. 

React uses Reactive Programming to create a front end architecture that updates views with streams of events as they occur in time. Changing a value will update a view in React.  

### React core features

React is built on three core features: Components, JSX, and Virtual DOM.     

#### Components 

**Components encapsulate state and view**. A component updates its view in response to changing values. 

> Pair up and read and dicsuss this "A Simple Component" at [https://reactjs.org](https://reactjs.org). Test the code sample and do your best to explain what's going on here. 

What you need to know: 

- React Projects are built from components
- Most of your work with React will be writing components. 
- Components can be nested one within another. In other words, a component can have children or be the child of another component
- Components are objects. You can make instances of them. 
- Components encapsulate both logic (methods and code), state (properties), and a view (components render themselves.)

#### JSX

**JSX is an extension of the JavaScript language**. It allows you to write code using an XML like syntax alongside regular JavaScript. 

JSX is compiled into vanilla JavaScript.

> Pair up and copy the code in the Simple Component example. Go to [Babel](https://babeljs.io/repl/#?presets=react&code_lz=MYewdgzgLgBApgGzgWzmWBeGAeAFgRgD4AJRBEAGhgHcQAnBAEwEJsB6AwgbgChRJY_KAEMAlmDh0YWRiGABXVOgB0AczhQAokiVQAQgE8AkowAUAcjogQUcwEpeAJTjDgUACIB5ALLK6aRklTRBQ0KCohMQk6Bx4gA) and paste the code into the left panel of the editor. Look at and discuss what appears in the right side of the editor. 

What you need to know: 

- The _view_ of a component is written in JSX
- JSX is an _extension_ of the JavaScript language 
- JSX compiles to _vanilla JavaScript_ 
- JSX has its own _special syntax_ (More on this in the tutorial)

#### Virtual DOM 

**Updating the DOM is a slow operation**. To speed this up React creates a virtual DOM. Manipulating the virtual DOM is much faster than manipulating the DOM directly.

> Pair up, read and dicuss the [Virtual DOM](https://reactjs.org/docs/faq-internals.html).

In a React App making changes to the DOM will often not work as expected since those changes will be overwritten by the virtual DOM! You should always rely on components to make changes to the DOM rather than you manipulating the outside of components. 

In other words, you won't see code like this `document.getElementById('name').innerHTML ='<h1>Hello</h1>'` in React apps!

ReactDOM looks at the virtual DOM and compares it real DOM making changes only where necessary. 

What you need to know: 

- React keeps track of all components in the virtual DOM.
- Making changes to DOM directly does not work with React! 
- Manipulating the DOM within a React project should almost always be handled with a Component!
    - In other words `document.getElementById()` is not compatible with React! 

## Activity

- `npx create-react-app ...`
- Creating Components
- Adding Styles

## Homework

- [Assignment 1](../Assignments/Assignment-01.md)

## After Class

- Challenge: [React tutorial](https://reactjs.org/tutorial/tutorial.html)

## Additional Resources

1. [ES6 Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
1. [tutorial](https://reactjs.org/tutorial/tutorial.html)
1. [JSX](https://reactjs.org/docs/introducing-jsx.html)
