# Redux Toolkit

The Redux Toolkit includes these APIs, which are built in methods? I think I don't really fully understand what an API is, maybe. 

- configureStore(): wraps createStore to provide simplified configuration options and good defaults. 

- createReducer(): that lets you supply a lookup table of action types to case reducer functions, rather than writing switch statements. 

- createAction(): generates an action creator function for the given action type string. The function itself has toString() defined, so that it can be used in place of the type constant.

- createSlice(): accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.
```
const counterSlice = createSlice({
  name: 'counter',
  initialState: 0,
  reducers: {
    increment: state => state + 1,
    decrement: state => state - 1
  }
})

const store = configureStore({
  reducer: counterSlice.reducer
})
```
- createAsyncThunk: accepts an action type string and a function that returns a promise, and generates a thunk that dispatches pending/fulfilled/rejected action types based on that promise

- createEntityAdapter: generates a set of reusable reducers and selectors to manage normalized data in the store

- The createSelector utility from the Reselect library, re-exported for ease of use.


[This link could be cool later when I understand things more](https://github.com/erikras/ducks-modular-redux)