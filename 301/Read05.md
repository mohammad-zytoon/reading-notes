# Putting it all together

**React Docs - thinking in React**

1. How would you break a mock into a component heirarchy?

 - FilterableProductTable (orange): contains the entirety of the example.
 - SearchBar (blue): receives all user input.
 - ProductTable (green): displays and filters the data collection based on user input.
 - ProductCategoryRow (turquoise): displays a heading for each category.
 - ProductRow (red): displays a row for each product.


 2. What is the single responsibility principle and how does it apply to components?

  - The single-responsibility principle (SRP) is a computer-programming principle that
    states that every module, class or function in a computer program should have responsibility 
    over a single part of that program's functionality, and it should encapsulate that part.


3. What does it mean to build a ‘static’ version of your application?

 - The easiest way is to build a version that takes your data model and renders the UI
 - To build a static version of your app that renders your data model, you’ll want to 
   build components that reuse other components and pass data using props.


4. Once you have a static application, what do you need to add?

 - To build your app correctly, you first need to think of the minimal set of mutable
   state that your app needs. The key here is DRY: Don’t Repeat Yourself. Figure out 
   the absolute minimal representation of the state your application needs and compute 
   everything else you need on-demand. For example, if you’re building a TODO list, 
   keep an array of the TODO items around; don’t keep a separate state variable for
   the count. Instead, when you want to render the TODO count, take the length of 
   the TODO items array.


5. What are the three questions you can ask to determine if something is state?

 - To figure out if a piece of data is a candidate for being state, you should ask 
   the following three questions. Is it passed in from a parent via props? If it is, it 
   probably isn't state. Does it remain unchanged over time? If it does, it probably isn't 
   state. Can you compute it based on any of the state or props in the component? If it can, 
   then it definitely isn't the state. Again, following our example of the filterable courses
   table,we can work out that the original list of courses can be passed in as props and does 
   not change over time, therefore it's not state. The search text the user enters, will probably 
   not remain and  changed over time therefore, it's likely to be state. The value of checkbox as 
   with the search text probably won't remain unchanged over time, so again, this is likely to be 
   state. The filtered list of courses can be computed by combining the original list of courses, 
   the search text and the checkbox value, therefore, it's not going to be state. It's difficult 
   to give you anything other than these guidelines to help, there's always a different way of doing 
   things and that's no different when you're trying to identify state in an application.


6. How can you identify where state needs to live?

 - Identify every component that renders something based on that state.

 - Find a common owner component (a single component above all the components 
   that need the state in the hierarchy).

 - Either the common owner or another component higher up in the hierarchy should own the state.

 - If you can’t find a component where it makes sense to own the state, create a new component 
   solely for holding the state and add it somewhere in the hierarchy above the common owner component.