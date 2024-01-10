---
title: Jekyll Admin Store
description: Store is the object that brings actions and reducers together.
---

## Middlewares

The Jekyll Admin Store is responsible for managing the state of the Jekyll Admin UI. It brings together actions and reducers to facilitate the functioning of the administrative interface. The store utilizes the following middlewares:

* **Redux Thunk** is a middleware that enables the creation of asynchronous action creators in Redux. It allows action creators to return a function, providing the ability to dispatch multiple actions and perform asynchronous operations. This is particularly useful for handling side effects such as API requests, allowing for dynamic actions based on the returned data. The usage of Redux Thunk facilitates the management of complex asynchronous logic within the Jekyll Admin Store.
* [Redux Logger](https://github.com/evgenyrodionov/redux-logger) - Logs fired actions to the console.
