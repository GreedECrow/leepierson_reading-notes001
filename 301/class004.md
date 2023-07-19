# React and Forms

## React Docs - Forms

### 1. What is a ‘Controlled Component’?
You can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

### 2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
I have no idea whether we should or not but since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.

### 3. How do we target what the user is entering if we have an event handler on an input field?
.target

## The Conditional (Ternary) Operator Explained

### 1. Why would we use a ternary operator?
Shorter code, same result.

### 2. Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

x===y ? value if true : value if false