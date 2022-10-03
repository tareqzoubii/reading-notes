**READING**
**React Docs - lists and keys**
**-------------**
**_What does .map() return?_**
>it takes an array and return it again with different values depending on developer needs
**_If I want to loop through an array and display each value in JSX, how do I do that in React?_**
> Use map() method.
**_Each list item needs a unique-----_**
>key 
**_What is the purpose of a key?_**
>Keys help React identify which items have changed, are added, or are removed.
[Resourse](https://reactjs.org/docs/lists-and-keys.html)
**The Spread Operator**
**_What is the spread operator?_**
>spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments
**_List 4 things that the spread operator can do?_**
>Copying an array,Using Math functions,Combining objects and converting NodeList to an array
**_Give an example of using the spread operator to combine two arrays._**
>const myArray = [`🤪`,`🐻`,`🎌`]
>const yourArray = [`🙂`,`🤗`,`🤩`]
>const ourArray = [...myArray,...yourArray]
>console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
**_Give an example of using the spread operator to add a new item to an array._**
>const fewFruit = ['🍏','🍊','🍌']
>const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
>console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌"
**_Give an example of using the spread operator to combine two objects into one_**
 >const objectOne = {hello: "🤪"}
>const objectTwo = {world: "🐻"}
>const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
>console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
>const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.>log("😂".repeat(5))}}
>objectFour.laugh() // 😂😂😂😂😂
[Resourse](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
**VIDEO**
**How to Pass Functions Between Components**
**_n the video, what is the first step that the developer does to pass functions between components?_**
>Create a function wherever the state is
**_In your own words, what does the increment function do?_**
>It increase the value of index in array 
**_How can you pass a method from a parent component into a child component?_**
>Using this.method name 
**_How does the child component invoke a method that was passed to it from a parent component?_**
>I need to invoke it like a props in that child component
[Resourse](https://www.youtube.com/watch?v=c05OL7XbwXU)
**BREAK**
**Things I want to know more about**
> i want to know more about bootstrap