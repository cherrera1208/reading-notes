Reading: Application State with Redux
=====================================

Reading
-------

[Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)

1. What is the first principle of Redux?
    * the single immutable state-tree, or that the entire state of the the application is represented by a single JS object
2. what is a store and what do we use our reducers for within that store?
    * store holds the entirety of the state tree
3. Name three Redux store methods given to us by createStore and describe their use.
    * `getState()`: returns the current state tree
    * `dispatch(action)`: Dispatches an action. This is the only way to trigger a state change
    * `subscribe(listener)`: Adds a change listener. It will be called any time an action is dispatched, and some part of the state tree may potentially have changed
4. Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.
    * it takes like items (the reducers from different objects) and puts them in a single store

Bookmark and Review
-------------------

[worlds easiest guide to redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

[testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Redux Docs](https://redux.js.org/)
