# State and Props

## React Lifecycle
[React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1. Render comes before the component did mount
2. the first thing to happen in the lifecycle of react is mounting the constructor 
3. things happen in the following order
  - constructor
  - render
  - component did mount
  - react updates
  - component will unmount
4. component did mount is used to load in things from a network request or DOM

## React State vs Props
[React State v Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

1. You can pass in render content
2. props cant be changed while state can be
3. whenever the state is changed
4. You could store an updating counter in a state
