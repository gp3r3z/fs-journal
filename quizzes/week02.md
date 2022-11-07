# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?

<!-- enter you answer in the space below -->

```
The keywords used to declare a variable are var, const and let. Each with their scopes but let is the new favorite variable over var.
```

**2.** What is the definition of a function?

<!-- enter you answer in the space below -->

```
Javascript function is a subprogram designed to perform a particular task
```

**3.** What are the `SOLID` principles?

<!-- enter you answer in the space below -->

```
The SOLID principles we learned from class are :
  +S - Single responsibility for a class
  +O - Open or Closed lasses should be closed for modification but open for extension
  +L - Liskove substitution parent classes should be easily substituted with their child classes without blowing up the application
  +I - Interface segregation many client interfaces are better than one general interface
  + D - Dependency inversion classes should depend on abstraction but not on concretion


  Codeworks' https://codeworksacademy.com/fs-student-guide/vocab/04-Principles-and-Patterns
```

**4.** Given this array:

```js
let fruit = ["apple", "banana", "pineapple", "orange", "strawberry"];
```

What index is the pineapple's current position? How do you know?

<!-- enter you answer in the space below -->

```
The pineapple is in the index of 2. We can determine this because the fruit is an array and starts at an index of 0.
```

**5.** With these two objects:

```js
let you = { name: "You", hair: true, friends: [] };
let them = { name: "Them", hair: false, friends: [] };
```

how would you .push the `them` object into the `you` object's array of friends?

<!-- enter you answer in the space below -->

```
We can push the 'them' object into the the 'you' object by first using dot notation to access the friends key array.We can then utilize the array push method to add the 'them' object to the friends array.
Ex:
  - you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:

<!-- enter you answer in the space below -->

```
if( i > 0 ){
  Do this
}else{
  do this
}
```

**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "**\_\_**" space? What would you put here to increase `i` by one on every iteration?

```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```

<!-- enter you answer in the space below -->

```
The for loop takes in 3 arguments , the initial value to be executed, the condition on when to execute and lastly the value to increment after the loop has been executed.
```

**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?

<!-- enter you answer in the space below -->

```
The DOM stands for the document object model and defines the logical structure of the documents and the way a document is accessed and manipulated. the index file is the first file access to render the DOM
```

**9.** What are the `9` ECMAScript types as defined by MDN?

<!-- enter you answer in the space below -->

```
The 9 types are undefined, null, boolean, number, bigint, string, symbol, and object.

```

**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?

<!-- enter you answer in the space below -->

```
Parameters are values that can be passed into a function meanwhile an argument is what is actually passed at function execution.
```

**11.** What is the difference between a `primitive` value and a `reference` value?

<!-- enter you answer in the space below -->

```
Reference values are types of objects and do not store primitive values like strings, boolean, undefined, null, or symbols.
```
