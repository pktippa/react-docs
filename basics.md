# Basics

Notes from Youtube code with Mosh

## Component

Atleast one root component called "App".

Every react app is essentially a tree of components.

From code perspectice a component is a class with state and render method.

React keeps a light weight representation of DOM in memory as Javascript objects that is referring to the 
virtual DOM.

When we change the state of the component we get new React element.

React will compare the state of this element and with its children detects the changes and applies them to Real DOM
to keep in sync with Virtual DOM

till 4:11