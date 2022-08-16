# Class-02: State and Props

## Topic Summary

The React lifecycle consists of three major parts, the mounting, updating, and unmounting phases. There is more detail to it than that, and the descriptions are full of jargon, but it's pretty straightforward.
Also, prop and state are two important concepts about react componenets and it is vital to understand the difference.

## Readings

### [React Lifecycle](https://medium.com/%40joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

- Questions:

  1.Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

  2.What is the very first thing to happen in the lifecycle of React?

  3.Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`

  4.What does `componentDidMount` do?

- Answers:

  1. render

  2. The constructor is called

  3. constructor > render > React Updates > componentDidMount > componenetWillUnmount

  4. Where initializations requiring DOM nodes should be, and where remote endpoint data should be instantiated. Also, a good place for subscriptions.

### [React State vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

- Questions:

  1.What types of things can you pass in the props?

  2.What is the big difference between props and state?

  3.When do we re-render our application?

  4.What are some examples of things that we could store in state?

- Answers:

  1. Componenets that are initialized to or to be rendered. Similar to things passed through a function.

  2. State is handled in the componenet, props are handled outside the componenet.

  3. When the state is updated in the component.

  4. The video example is a counter. The initial value of the counter is determined by the the prop value, while the updated value handled by the computer is in the state.

## Bookmark and Review

- [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

- [React Docs - handling events](https://reactjs.org/docs/handling-events.html)

- [React Tutorial through ‘Developer Tools](https://reactjs.org/tutorial/tutorial.html)

- [React Bootstrap Documentation](https://react-bootstrap.github.io/)

- [Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

- [Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)

- [Netlify](https://www.netlify.com/)

## Things I Want to Know More About

This was a brief overview of the topics, so it didn't get too in depth. I would like to read over the specifics of these topics to be more knowlegable on the subjects.
