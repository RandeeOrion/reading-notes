# Redux: Combined Reducers

- Combined Reducers are simply multiple reducers pulled into one object in a particular file.

- This makes it easier for each reducer to do only one thing and be more flexible in their use. 

- The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

```
rootReducer = combineReducers({potato: potatoReducer, tomato: tomatoReducer})
// This would produce the following state object
{
  potato: {
    // ... potatoes, and other state managed by the potatoReducer ...
  },
  tomato: {
    // ... tomatoes, and other state managed by the tomatoReducer, maybe some nice sauce? ...
  }
}
```