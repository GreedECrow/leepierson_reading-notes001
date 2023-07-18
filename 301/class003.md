# Passing Functions as Props

## React Docs - lists and keys

### 1. What does .map() return?
Lists of componants.

### 2. If I want to loop through an array and display each value in JSX, how do I do that in React?
Loop through the numbers array using the JavaScript map() function. We return a <li> element for each item. Finally, we assign the resulting array of elements to listItems. Then, we can include the entire listItems array inside a <ul> element.

### 3. Each list item needs a unique ____.
key attribute.

### 4. What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

## The Spread Operator

### 1. What is the spread operator?
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

### 2. List 4 things that the spread operator can do.
- Adding items
- Combining arrays
- Spreading an array
- Expands’ an iterable object

### 3. Give an example of using the spread operator to combine two arrays.
To combine two or more arrays, you can either use the functional method []. concat(arr1, arr2) or the spread operator [...arr1,...arr2]. The merging outcome is kept in a new array, making these methods immutable.

### 4. Give an example of using the spread operator to add a new item to an array.
One common method that web developers use is the .push() method. In-addition, you can use the spread (…) operator to add new items to an array.

### 5. Give an example of using the spread operator to combine two objects into one.
To merge two objects in JavaScript, you can use the spread ... operator. The spread operator creates a new object with all the properties from the first and second object. If there's two properties with the same name, the property from the second object wins.

## How to Pass Functions Between Components


### 1. In the video, what is the first step that the developer does to pass functions between components?
Creates a Function.

### 2. In your own words, what does the increment function do?
It checks for a match on the name. If it does match, the count goes up.

### 3. How can you pass a method from a parent component into a child component?
?

### 4. How does the child component invoke a method that was passed to it from a parent component?
?