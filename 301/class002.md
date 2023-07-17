# State and Props

## React lifecycle

### 1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
Render

### 2. What is the very first thing to happen in the lifecycle of React?
Mounting

### 3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
- Constructor
- Render
- React Updates
- ComponentDidMount
- ComponentWillUnmount

### 4. What does componentDidMount do?
 If you need to load anything using a network request or initialize the DOM, it should go here.

## React State Vs Props

### 1. What types of things can you pass in the props?
Props are like arguments to a function.

### 2. What is the big difference between props and state?
Props are handled outside of the componant and passed in. State is handled inside of the componant.

### 3. When do we re-render our application?
When you change the state inside the application.

### 4. What are some examples of things that we could store in state?
- Input element
- Check box
- Select box