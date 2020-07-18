# Redux - Asynchronous Actions

- Async functions need to have time to make their call, thus, Thunk comes into play to help make sure code doesn't break if your async call isn't finished before you need to use that data. 


- Thunk allows us to make async and sync functions that work properly within redux. By wrapping the function in thunk, we can make fetch calls and returns an object that is more flexible. 