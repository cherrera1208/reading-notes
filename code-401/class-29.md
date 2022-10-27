Reading: Advanced State with Reducers
=====================================

Reading
-------

[useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

1. Name an alternative to the `useState` Hook.
    * useReducer
2. Why might the `useReducer` Hook be preferable to the `useState` Hook?
    * when you have complex state logic that involves multiple sub-variables or when the next state depends on the previous one.
3. What are two ways to set the initial state?
    * 1) pass the initial state as a second argument, e.g.

    ```js
      const [state, dispatch] = useReducer(
    reducer,
    {count: initialCount}  );
    ```

    and 2) create an initial state *lazily* by passing an init function as the third argument

[Ultimate Guide to useReducer](https://blog.logrocket.com/guide-to-react-usereducer-hook/)

1. In terms of state, what does `useReducer` expect to receive as a parameter?
    * accepts a reducer function and the initial state as params
2. What does `useReducer` return?
    * an array that holds the current state value and a dispatch function to which you can pass an action and later invoke it
3. Explain `dispatch` to a non-technical recruiter.
    * it takes an object and tells the reducer what that object requests of it. Like a phone dispatcher, it takes a request from one end then "dispatches" it to the function that need to execute the task
