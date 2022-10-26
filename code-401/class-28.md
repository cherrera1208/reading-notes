Reading: Component Lifecycle / `useEffect` Hook
===============================================

Reading
-------

[effects hook](https://reactjs.org/docs/hooks-effect.html)

1. What purpose does `useEffect` serve in a function component compared to its counterpart(s) in class components?
    * useEffect prevents duplicating code for side effects
2. When using the useEffect Hook:
    1. What does `useEffect` do?
        * the hook tells React that the component has something to do after render
    2. Why is `useEffect` called inside a component?
        * allows access to state variable (props) from the effect, i.e. it's already in scope
3. Explain the importance of properly implementing effects with Cleanup
    * cleanup prevents memory leaks
