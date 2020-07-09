# Application State with Redux

**Why would you wrap your entire application within a context?**

- This allows for easy 'setters' to be accessible throughout the whole application. 

**What is the purpose of a reducer?**

- A reducer is much like an event handler. It does things to states when a specific event is triggered. 

**What does an action contain?**

- Action contains the action type: onClick, onHover etc. and the payload that will have things done to it.

**Why do we need to copy the state in a reducer?**

- Because we have to figure out how we want to change it. And if we hold the prechange values, we can easily change the ones we want without mucking up the whole object. 