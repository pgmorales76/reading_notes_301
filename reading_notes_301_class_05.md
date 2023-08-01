[Home](https://pgmorales76.github.io/reading_notes_301/)

# Class 05 Reading Notes

## Why This Topic Matters

### Having the ability to "think in React" enables the developer to build components/applications, at scale, in an efficient manner

## *What is the `single responsibility principle` and how does it apply to components?*

### A component should, ideally, only be responsible for one aspect of your application. If it grows to multiple responsibilities, it should be decomposed into multiple components

## *What does it mean to build a ‘static’ version of your application?*

### Building a 'static' version renders the UI, from your data model, without adding any interactivity (yet!)

## *Once you have a static application, what do you need to add?*

### To make the UI interactive, you need to use *state* to allow users to change the underlying data model

## *What are the three questions you can ask to determine if something is state?*

1. Does it remain unchanged over time?
2. Is it passed in from a parent via props?
3. Can you compute it based on existing state or props in your component?

## *How can you identify where state needs to live?*

### For each piece of state in your application, you should identify every component that renders something based on that state, find their closest common parent component, and decide where the state should live by:

1. Put the state directly into their common parent; or,
2. Put the state into some component above their common parent; or,
3. If you can’t find a component where it makes sense to own the state (e.g., in steps 1, or 2), create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.

[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

## *What is a “higher-order function”?*

### Functions that operate on other functions, either by taking them as arguments, or by returning them

## *Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?*

    function greaterThan(n) {
    return m => m > n;
    }
    let greaterThan10 = greaterThan(10);
    console.log(greaterThan10(11));
    // → true

### It's returning a function, which acts upon the parameter from the `greaterThan` function, to produce a value which makes the statement evaluate to `truthy`

## *Explain how either `map` or `reduce` operates, with regards to higher-order functions.*

### `map()` transforms an array by applying a function to all of its elements, then builds a new array. The new array's elements are "mapped" by the function, and given a different "shape"

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

## Things I Want to Know More About

### A callback function seems to be similar to a higher-order function. Is this true?

### Would one be correct in saying a callback function is a "lower-order function", in that a callback function appears lower in the code?
