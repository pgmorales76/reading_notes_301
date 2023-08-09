[Home](https://pgmorales76.github.io/reading_notes_301/)

# Class 10 Reading Notes

## Why This Topic Matters

### Understanding the call stack is crucial to understanding a part of how the JavaScript engine works

### Understanding error messages enables the developer to correct bugs in their code

## *What is a ‘call’?*

### A function invocation

## *How many ‘calls’ can happen at once?*

### Because the call stack is synchronous, single functions are executed one at a time, from top to bottom

## *What does LIFO mean?*

> LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns. [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

## *Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.*

    function greeting() {
    // [1] Some code here
    sayHi();
    // [2] Some code here
    }
    function sayHi() {
    return "Hi!";
    }

    // Invoke the `greeting` function
    greeting();

    // [3] Some code here

[MDN Call Stack Example](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack#example)

## *What causes a Stack Overflow?*

> A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error. [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

[Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

## *What is a ‘reference error’?*

### Trying to use a variable that isn't declared

## *What is a ‘syntax error’?*

### When something can't be parsed, in terms of syntax, such as a speling error (LOL)

## *What is a ‘range error’?*

### Giving an object an invalid length, such as giving an array negative length

## *What is a ‘type error’?*

### Using, or accessing, data types that are incompatible

## *What is a breakpoint?*

### A point in your code that breaks the execution, enabling the developer to examine, and debug, their code

## *What does the word ‘debugger’ do in your code?*

![Debugger Statement](/images/debugger_statement.webp)

> I’ve added a debugger statement and when running the code above you can see the “history” before reaching that breakpoint. In this case it’s not a long call stack but you can start to see why it is useful, you know the function add was executed in line 14, with what parameters (which you an see in the scope below the call stack) and you can evaluate whatever will well you at that point in the console, in this case evaluation result.split(‘’) would show you that the result being returned would be [“1”, “2”]. [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

## Things I Want to Know More About

### Is the data structure for the call stack, including FILO, similar with other technologies, or is it different?

### Should a debugger statement always be included in your code?
