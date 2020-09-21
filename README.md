#https://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux


Why do we need middleware for async flow in Redux?



The common approach to integrate asynchronous tasks into the Redux architecture is to break an asynchronous action into at least three synchronous actions.

An action informing that the asynchronous task:

started
was successfully completed
failed
