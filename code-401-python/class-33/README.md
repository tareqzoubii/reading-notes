# Read 33

## Custom Hooks

#### What is custom Hooks in React?
> Custom React JS hooks are reusable functions that a React JS software developer can use to add special and unique functionality to the React applications. Usually, if there is a requirement to add a feature, one can install a third-party library and solve the problem.

#### What do custom Hooks usually do?
> The main reason to write a custom hook is for code reusability. For example, instead of writing the same code across multiple components that use the same common stateful logic (say a “setState” or localStorage logic), you can put that code inside a custom hook and reuse it.

#### What is memoization techniques?
> In computing, memoization or memoisation is an optimization technique used primarily to speed up computer programs by storing the results of expensive function calls and returning the cached result when the same inputs occur again.

#### How do you Memoize a component?
> Since components are just functions though, they can be memoized using React. memo() . This prevents the component from re-rendering unless the dependencies (props) have changed. If you have a particularly heavy component then it is best to memoize it, but don't memoize every component.