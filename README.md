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

## Resources
Udemy- [Modern React with Redux](https://www.udemy.com/react-redux/learn/v4/overview)
