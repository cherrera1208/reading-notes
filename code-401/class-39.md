Readings: Redux - Additional Topics
===================================

Reading
-------

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

1. What concerns are addressed by Redux Toolkit?
    * "Configuring a Redux store is too complicated"
    * "I have to add a lot of packages to get Redux to do anything useful"
    * "Redux requires too much boilerplate code"
2. What does `configureStore()` do?
    * wraps `createStore` to provide simplified config options and good defaults
3. How would I use `createSlice()`?
    * accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

[MobX](https://mobx.js.org/getting-started.html)

1. What is Mobx?
    * is a simple, scalable and battle tested state management solution that makes it impossible to produce an inconsistent state.
2. How does MobX make it “impossible” to produce an inconsistent state?
    * make sure that everything that can be derived from the application state, will be derived. Automatically.
3. How would we build a reactive user interface?
    * using a toolkit like mobx to ensure that state is not inconsistent

Tutorial
--------

[Tutorial](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)

1. What take-away(s) did this tutorial provide?
    * redux is tricky but has a lot of neat features

Bookmark and Review
-------------------

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

[HookState](https://hookstate.js.org/)
