[Home](https://pgmorales76.github.io/reading_notes_301/)

# Class 02 Reading Notes

## Why This Topic Matters

### Understanding the life cycle of a React app is key to being able to writing, delivering, and troubleshooting your app

### Understanding the difference between State and Props will enable a developer to 

## **Reading**

## *Based off the diagram, what happens first, the ‘`render`’ or the ‘`componentDidMount`’?*

### `render`

## *What is the very first thing to happen in the lifecycle of React?*

### During the "Mounting Phase", an instance of a component is created and inserted in the DOM

## *Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor` , `componentWillUnmount`, `React Updates`.*

### `constructor`, `render`, `React Updates`, `componentDidMount`, and `componentWillUnmount`

## *What does `componentDidMount` do?*

> This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

[React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

## **Videos**

## *What types of things can you pass in the props?*

### Things you pass to a function, what you want to initialize a component to, or, what you want your component to render like, or data that is static.

## *What is the big difference between props and state?*

### You can think of props as arguments to a function. Props you pass into a component. Props are handled outside a component

### State is something inside a component. State is handled within the component. Think of it as the component's "state of affairs". What is stored in state is dynamic, rather than static, data

## *When do we re-render our application?*

### When your props are different, or, when you change the state inside of your application

## *What are some examples of things that we could store in state?*

### Storing what you need to be updating, such as a counter. Storing input data from a user

[React State versus Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

## **Bookmark and Review**

[React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

[React Docs - Handling Events](https://reactjs.org/docs/handling-events.html)

[React Tutorial through 'Developer Tools'](https://reactjs.org/tutorial/tutorial.html)

[React Bootstrap Documentation](https://react-bootstrap.github.io/)

[Bootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

[Bootstrap Shuffle - A Class Sandbox](https://bootstrapshuffle.com/classes)

[Netlifly](https://www.netlify.com/)

## Things I Want to Know More About

### Is there ever an instance where state is handled outside the component? Is there ever an instance where props are handled within the component?

### Do modern apps ever not have state? Do they ever not have props?
