# Rect with Redux Weather App

## Project Purpose
- Solidify knowledge of React
- Get much more framilier with Redux
- Make Async calls with Redux

## What I Learned
- Middleware- has the ability to block, modify, or passthrough actions
before they hit a reducer.
- Application state is only changed through actions and reducers.
- Actions always have to return a type.
- Use const to hold action type to prevent errors from being easily created later.
- axios- a library sole made for making AJAX requests from the browser.
- Redux promise looks at the payload property, if the property is a promise Redux stop
and runs the promise. If the promise retruns Redux replaces the payload property with the
result of the promise and sends that to the reducer.
- When inside a reducer never mutate state, always return a comletely new instace of state.
- ES6 create new array [ action.payload.data, ...state ];, this will take the original state = []
and create an new array with the new data as the first record in the array with the existing (...state)
data in the same array.
-ES6 setting a function variable in the arguments function myFunction( { myArgument } ) {}.  This will
create a const inside the function.
-React when rendering a list a unique key value must be provided in the top level element.
-Used React Sparklines to quickly create charts
## Resources
Udemy- [Modern React with Redux](https://www.udemy.com/react-redux/learn/v4/overview)
