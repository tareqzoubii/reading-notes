**_What is the single responsibility principle and how does it apply to components?_**
>It's a technique that a component should ideally only do one thing.
>
**_What does it mean to build a ‘static’ version of your application?_**
> it means a way to convert data model and render it in uitree.
**_Once you have a static application, what do you need to add?_**
>inside the component add state that navigate the data after updates
**_What are the three questions you can ask to determine if something is state?_**
>Q1:Is it passed in from a parent via props? If so, it probably isn’t state.
>Q2:Does it remain unchanged over time? If so, it probably isn’t state.
>Q3:Can you compute it based on any other state or props in your component? If so, it isn’t state.
**_How can you identify where state needs to live?_**
>1. Identify every component that renders something based on that state.
>2. Find a common owner component (a single component above all the components that need the state in the hierarchy).
>3. Either the common owner or another component higher up in the hierarchy should own the state.
>4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
[RESOURSE](https://reactjs.org/docs/thinking-in-react.html)
**_What is a “higher-order function”?_**
>Functions that operate on other functions, either by taking them as arguments or by returning them
**_Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?_**
>it's comparing two functions with each others,
**_Explain how either map or reduce operates, with regards to higher-order functions._**
>The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array.
[RESOURSE](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

**Things I want to know more about**
>i want to know more about sort method