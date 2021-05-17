# Passing Functions as Props

- What does .map() return? it is an iterator that yields items on demand.

- If I want to loop through an array and display each value in JSX, how do I do that in React?
  by the map() function.

- Each list item needs a unique key.

- What is the purpose of a key? help React identify which items have changed, are added, or are removed.



- What is the spread operator? is a new addition to the set of operators in JavaScript ES6.

-  Things that the spread operator can do:
    
   - Copying an array.
   - Concatenating or combining arrays.
   - Using Math functions.
   - Using an array as arguments.

- Give an example of using the spread operator to combine two arrays:
- const arr1 = [1,2,3]
  const arr2 = [4,5,6]
  const arr3 = [...arr1, ...arr2] //arr3 ==> [1,2,3,4,5,6].


- Give an example of using the spread operator to add a new item to an array:

- let numberStore = [0, 1, 2];
  let newNumber = 12;
  numberStore = [...numberStore, newNumber]; .


- Give an example of using the spread operator to combine two objects into one:
- let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
}; /



- what is the first step that the developer does to pass functions between components?
  
  - increament function

- what does the increment function do?
  
  - increase the counter  , when we click on add button.

- How can you pass a method from a parent component into a child component?

  - A parent component defines a function.
  - The function is passed as a prop to a child component.
  - The child component then invokes the prop.
  - The parent function is then called, usually changing something.
  - Then the parent component is re-rendered along with its children.


- How does the child component invoke a method that was passed to it from a parent component?

  - by this order:(this.refs.REF_NAME.METHOD_NAME)
