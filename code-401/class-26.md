Reading: Component Based UI
===========================

Reading
-------

[react hello world](https://facebook.github.io/react/docs/hello-world.html)

1. What are the building blocks of a React app?
    * elements and components
2. What is the difference between an element and a React component?
    * elements are like HTML DOM elements written with JSX and components are the reusable snippets of code written in their own directories in the program
3. What are some advantages of React’s component based architecture?
    * reusability and scalability. You can reuse the components throughout your app so there's less chance of making careless bugs and they can be changed if necessary, kind of like a function

[introducing JSX](https://facebook.github.io/react/docs/introducing-jsx.html)

1. What is JSX and why do we use it?
    * JSX is like DOM manipulation but is written like standard HTML directly in JS
2. Describe the process of embedding JavaScript expressions in JSX.
    * import the component, recall the component in angle brackets, use a frag if there will be multiple parent level elements, then fill it out like an HTML page
3. Is it safe to embed user input in JSX? Explain.
    * yes because React escapes any values embedded in JSX before rendering

[rendering elements](https://facebook.github.io/react/docs/rendering-elements.html)

1. Explain what a React Component is to a non-technical friend.
    * think of a single component of any complex machine, for example, the transmission of a car. Within reason, that transmission can be moved from one car to other (of similar make and condition) and it can even be upgraded of downgraded to some degree.
2. Describe mutability and React Components, specifically, how is the UI updated?
    * components are mutable, i.e. they --their state-- can be changed. When this change of state occurs, say from user input, the UI will update accordingly.
3. If changes are made to the UI, what does React update?
    * The state

Bookmark and Review
-------------------

* [sass cheatsheet](https://devhints.io/sass)
* [react cheatsheet](https://devhints.io/react)
* [another react cheatsheet](https://reactcheatsheet.com/)
