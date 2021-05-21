# Working with Redux

## React

https://reactjs.org/

## Ecosystem

https://redux.js.org/introduction/ecosystem

## JavaScript Immutability

https://immutable-js.github.io/immutable-js/

### Store

A store holds the whole state tree of application. The only way to change the state inside it is to dispatch an action on it.

### Store Methods

1. getState() : Returns the current state tree of your application. It is equal to the last value returned by the store's reducer.

2. dispatch(action) : Dispatches an action. This is the only way to trigger a state change.

3. subscribe(listener) : Adds a change listener. It will be called any time an action is dispatched, and some part of the state tree may potentially have changed. You may then call getState() to read the current state tree inside the callback.