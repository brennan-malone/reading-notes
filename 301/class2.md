# State and Props

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
   * The render step happens first
2. What is the very first thing to happen in the lifecycle of React?
   * Mounting of the constructor
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
   * constructor, render, componentDidMount, React Updates, componentWillUnmount
4. What does componentDidMount do?
   * used to invoke after a component is mounted. This is a good metho to use to setup any subscriptions or network based resources.

## React State Vs Props

1. What types of things can you pass in the props?
   * any javascript value, such as objects, arrays, functions.
2. What is the big difference between props and state?
   * State is internal and is controlled by the componenet itself. Props is external and is controlled by whatever renders the component.
3. When do we re-render our application?
   * when the state changes in the parent component all components will need to re-render
4. What are some examples of things that we could store in state?
   * State is good to hold state information about the UI instead of actual data. We want to hold whether or not a user did something.