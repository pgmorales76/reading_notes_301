[Home](https://pgmorales76.github.io/reading_notes_301/)

# Class 04 Reading Notes

## Why This Topic Matters

### Just like in HTML, forms are important interactive function for websites

### In React, we learn a more efficient way of building forms with JSX, rather than with vanilla HTML

## *What is a ‘Controlled Component’?*

### In HTML, form elements such as `<input>`, `<textarea>`, and `<select>` typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState()

### We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a **“controlled component”**

## *Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?*

### Since the `value` attribute is set on our form element, the displayed value will always be `this.state.value`, making the React state the source of truth. Since `handleChange` runs on every keystroke to update the React state, the displayed value will update as the user types

### With a controlled component, the input’s value is always driven by the React state. You can pass the value to other UI elements too, or reset it from other event handlers

## *How do we target what the user is entering if we have an event handler on an input field?*

### In React, a `<textarea>` uses a `value` attribute instead. This way, a form using a `<textarea>` can be written very similarly to a form that uses a single-line input

### When you need to handle multiple controlled `input` elements, you can add a `name` attribute to each element and let the handler function choose what to do based on the value of `event.target.name`

[React Docs - Forms](https://reactjs.org/docs/forms.html)

## *Why would we use a ternary operator?*

### More efficient code

## *Rewrite the following statement using a ternary statement:*

    if(x===y){
        console.log(true);
    } else {
        console.log(false);
    }

    if ( condition ) {
        value if true;
    } else {
        value if false;
    }

    condition ? value if true : value if false

    x===y ? console.log(true) : console.log(false)

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

[React Boostrap - Forms](https://react-bootstrap.github.io/forms/overview/)

[React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

## Things I Want to Know More About

### Are there scenarios when you **SHOULDN'T** use a ternary operator?
