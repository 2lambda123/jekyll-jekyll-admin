---
title: Store
description: Store is the object that brings actions and reducers together.
---

## Middlewares

The store has the following middlewares;

To run the unit tests for the new middleware, follow these steps:
1. Navigate to the `tests` directory.
2. Run the command `npm test` to execute all unit tests.
**Note:** Ensure that all dependencies are installed before running the tests.

* [Redux Thunk](https://github.com/gaearon/redux-thunk) - middleware for handling asynchronous actions. It allows action creators to return a function, instead of an action object, which can be used to dispatch multiple actions or perform async logic.
* [New Middleware Name](https://new-middleware-docs) - Description of the new middleware. Unit tests are available for this middleware. See the test file [middleware.spec.js](tests/middleware.spec.js) for details on how to run the unit tests.
