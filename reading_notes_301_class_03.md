[Home](https://pgmorales76.github.io/reading_notes_301/)

# Class 03 Reading Notes

## Why This Topic Matters

### Being able to, seemlessly, have your components connected will allow your app to run smoothly, and allow for easier troubleshooting

### A well-made component family tree makes creating more complicated apps less difficult

## **Reading**

## *What does .map() return?*

### A new array with the results of a callback function, iterated on each element, from the original array

## *If I want to loop through an array and display each value in JSX, how do I do that in React?*

### Embed an expression in curly braces

## *Each list item needs a unique ____.*

### key

## *What is the purpose of a key?*

### They help React identify items which have changed, added, or, removed

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html).

## *What is the spread operator?*

### An operator which allows an array to be expanded. The spread operator "spreads" an array into separate arguments

## *List 4 things that the spread operator can do.*

### Copying an array; using math functions; adding an item to a list; and, adding to state in React

## *Give an example of using the spread operator to combine two arrays.*

    let arr1 = [0, 1, 2];
    let arr2 = [3, 5, 7];
    let primes = [...arr1, ...arr2];

    // > [0, 1, 2, 3, 5, 7]

[Spread Syntax](https://howchoo.com/javascript/how-to-merge-two-arrays-in-javascript#spread-syntax)

## *Give an example of using the spread operator to add a new item to an array.*

    const fewFruit = ['🍏','🍊','🍌']
    const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
    console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

[Adding an item to a list](https://gist.githubusercontent.com/djD-REK/fe282feb0b84a5f1a50fd0b2e7e5510e/raw/4f291907917d3cbd9cbfcd000a218dbda4f18274/Adding%20an%20item%20to%20a%20list.js)

## *Give an example of using the spread operator to combine two objects into one.*

    const objectOne = {hello: "🤪"}
    const objectTwo = {world: "🐻"}
    const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
    console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
    const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
    objectFour.laugh() // 😂😂😂😂😂

[Combining objects](https://gist.githubusercontent.com/djD-REK/1995aa70063ce1cadc126ae523626e19/raw/4823db5f5f893af1848c03804f832340dd750fe0/Combining%20object%20properties%20and%20methods%20with%20spread%20operator.js)

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## **Videos**

## *In the video, what is the first step that the developer does to pass functions between components?*

### Using the `this` keyword

## *In your own words, what does the `increment` function do?*

### It increments the count property for the particular object that's clicked

## *How can you pass a method from a parent component into a child component?*

### With a prop passing a function

## *How does the child component invoke a method that was passed to it from a parent component?*

### Using a callback function from the parent component and using an argument value as a prop 

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

## **Bookmark and Review**

[React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)

[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

## Things I Want to Know More About

### How many "generations" in a component family tree are there, generally? 
