**_What is functional programming?_**
>Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
**_What is a pure function and how do we know if something is a pure function?_**
>It returns the same result if given the same arguments and it does not cause any observable side effects
**_What are the benefits of a pure function?_**
>Pure functions are much easier to read
**_What is immutability?_**
>Mutable is a type of variable that can be changed. In JavaScript, only objects and arrays are mutable, not primitive values
**_What is Referential transparency?_**
>Referential transparency, a term commonly used in functional programming, means that given a function and an input value, you will always receive the same output. That is to say there is no external state used in the function

**_What is a module?_**
>file containing related code. In JavaScript, we use the import and export keywords to share and receive functionalities respectively across different modules.

**_What does the word ‘require’ do?_**
> it’s import any of methods or apps that installed in terminal 

**_How do we bring another module into the file the we are working in?_**
>use the import statement, followed by a comma-separated list of the features you want to import wrapped in curly braces, followed by the keyword from, followed by the path to the module file — a path relative to the site root, which for our basic-modules example would be /js-examples/module-examples/basic-modules.

**_What do we have to do to make a module available?_**
>by giving the module a name after we import it!

[RESOURCE](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)