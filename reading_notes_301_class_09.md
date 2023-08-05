[Home](https://pgmorales76.github.io/reading_notes_301/)

# Class 09 Reading Notes

## Why This Topic Matters

### Functional programming is important because working with immutable data requires more objects to have their own data. What this accomplishes is having the data "specialize", and "focus", in the same way a React component, ideally, has a single function

### Working with modules and `require()` reminds me using `import` and `export` to bring components in, or, send them out, from elsewhere, to be used in another component. So, this uses similar practices, with different technologies and across platforms, which is important because it makes development much easier, and more efficient

## **Reading**

## *What is functional programming?*

> Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data. [Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)

## *What is a pure function and how do we know if something is a pure function?*

- It returns the same result if given the same arguments (it is also referred as `deterministic`)

- It does not cause any observable side effects

## *What are the benefits of a pure function?*

### Because the code is easier to test, you don't need to mock anything. Therefore, pure functions may be unit tested in different contexts

## *What is immutability?*

### Data whose state is unchanging over time, or unable to be changed. Instead of changing immutable data, you must create a new object, with a new value

## *What is Referential transparency?*

> Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
>
> pure functions + immutable data = referential transparency
>
> [Concepts of Functional Programming in Javascript](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

[Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

## **Videos**

## *What is a module?*

### A JavaScript file

## *What does the word ‘require’ do?*

- It uses the global object, in `Node.js`, so you can use it whereever you are.

- It uses the functionality, created in one module, in another module.

- You're **requiring** the module passed to `require()`.

## *How do we bring another module into the file we are working in?*

### `var another_module = require(another_module);`

## *What do we have to do to make a module available?*

### `module.exports = variabe name of whatever you want to be made available, outside of this module;`

[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

## Things I Want to Know More About

### In the video, the developer declares a variable, then assigns it a function, as a value. When they invoke the function, they use the name of the variable, with the parentheses notation. Is this a "best practice"? I haven't seen this, before (although, that's not saying much, mind you! LOL). You can invoke a function by calling the variable name, to which that function had been assigned as a value, and use parenthesis on that variable name, which the code treats as invoking a function? This is something I'd like more information on
