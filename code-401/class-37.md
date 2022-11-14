Readings: Redux - Combined Reducers
===================================

Reading
-------

[Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

1. Why create multiple reducers?
    * as the app grows, it's smart to separate functions so each is managing independent parts of state
2. How would you combine multiple reducers?
    * the `combineReducer()` method and pass it to `createStore` function
3. How will you manage state as an immutable object? why?
    * return a new state object because redux is an immutable state tree

[Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

1. `combineReducers` is a utility function to simplify the most common use case when writing _____ .
    * reducers
2. Explain how `combineReducers` assembles the new state tree.
    * takes an object full of slice reducer functions, and creates a function that outputs a corresponding state object with the same keys
3. How would you define initial state in an app using `combineReducers`?
    * either `createStore` or `preloadedState`

[Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

1. Why will you want to split your reducing functions as your app becomes more complex?
    * separate functions so each is managing independent parts of state
2. The ___ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to __.
    * `combineReducer()` and `createStore`
3. What is a popular convention when naming reducers?
    * descriptive object and effect
