# Pulling it All Together

# Thinking in React
[Thinking in REact](https://reactjs.org/docs/thinking-in-react.html)

1. The single responsibility principle is that a component should only do 1 thing and if it grows to do more it should be broken down into smaller components.
2. Building a static version of the site is getting the layout done but not adding any interactivity
3. Next you need to identify the minimal UI state and you can use the acronym "DRY" Dont Repeat Yourself.
4. How to tell if something is state? (pulled from article):
  - Is it passed in from a parent via props? If so, it probably isn’t state.
  - Does it remain unchanged over time? If so, it probably isn’t state.
  - Can you compute it based on any other state or props in your component? If so, it isn’t state.
5. How to tell where state needs to live? (also pulled from article):
  - Identify every component that renders something based on that state.
  - Find a common owner component (a single component above all the components that need the state in the hierarchy).
  - Either the common owner or another component higher up in the hierarchy should own the state.
  - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


## Order Functions
[Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. Higher order functions are functions that take in other functions as arguments or by returning them.
2. line 2 of the function greaterThan() is returning another function.
3. Map allows you to apply a function to all the items in an array.
