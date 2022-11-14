Readings: Redux - Asynchronous Actions
======================================

Reading
-------

[async actions](https://redux.js.org/advanced/asyncactions)

1. Why use Redux middleware?
    * enables writing logic that has side effects
2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
    * state goes to dispatch then hits the middleware that makes an API call. After it receives a response from the API, the store changes the state via reducer
3. How are we accommodating async in our Redux app?
    * with thunk

[thunk middleware](https://github.com/reduxjs/redux-thunk)

1. Why would you need `redux-thunk` middleware?
    * if you need some delayed work to be performed
2. Redux Thunk middleware allows you to write action creators that return a ___ instead of an action.
    * an object to be dispatched
3. Describe how any return value from the inner thunk function will be made available.
    * is called as an action as it passes through middleware chain
