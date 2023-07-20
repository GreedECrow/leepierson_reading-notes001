# Putting it all together

## React Docs - Thinking in React

### 1. What is the single responsibility principle and how does it apply to components?
A component should only do one thing. If it gets too big, it should be decomposed into smaller subcomponents.

### 2. What does it mean to build a ‘static’ version of your application?
A build version that renders the UI from your data model without adding any interactivity. Building a static version requires a lot of typing and no thinking.

### 3. Once you have a static application, what do you need to add?
State values for users to change in the data model to make the app interactive.

### 4. What are the three questions you can ask to determine if something is state?
- Does it remain unchanged over time? If so, it isn’t state.
- Is it passed in from a parent via props? If so, it isn’t state.
- Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!

### 5. How can you identify where state needs to live?
- Identify components that use state.
- Find their common parent.
- Decide where the state lives.


## Higher-Order Functions

### 1. What is a “higher-order function”?
Functions that operate on other functions, either by taking them as arguments or by returning them.
Higher-order functions allow us to abstract over actions, not just values.

### 2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
I might be over thinking it but I cant figure out what the `m` is meant to be? Return m that is equal to or greater than m and greater than n? I've no clue. I'me guessing it adds something because it's reached m's threshold/max capacity?

### 3. Explain how either map or reduce operates, with regards to higher-order functions.
Nope. I am not grasping this at all.