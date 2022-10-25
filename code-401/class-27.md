Reading: `useState()` Hook
==========================

Reading
-------

[Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

1. What was the motivation for introducing Hooks?
    * to reuse stateful logic between components
2. What changes are important regarding implementing Hooks versus Component Classes?
    * hooks extract stateful logic from a component so it can be tested independently and reused
3. Hooks allow you to reuse stateful logic without changing _____.
    * component hierarchy

[hooks api](https://reactjs.org/docs/hooks-overview.html)

1. Name two rules imposed by React Hook usage.
    * only call hooks ... 1) at the top level, and 2) from the React function components
2. How would you identify a custom Hook and why might you create one?
    * a function whose name starts with "use" and may call other hooks. You can declare functions with states that you want to keep track of, like the example provided, a friend's online status

[the state hook](https://reactjs.org/docs/hooks-state.html)

1. What is a Hook?
    * a react feature that lets you use state without classes
2. When would I use the `useState` Hook?
    * if you need to add state to a function. useState sets the state directly in the function instead of this.state like in class
3. If you were to add React state to a function component by declaring a state variable:
    1. What does calling `useState` do?
        * declares a state variable to a function
    2. What do we pass to `useState` as an argument?
        * the initial state, can be an object, number, or string
    3. What does `useState` return?
        * a pair of values; the current state and the function that updates it

Bookmark and Review
-------------------

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)
