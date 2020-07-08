# Context API 

**What is the difference between the variables MyContext and MyProvider in the examples above?**

- MyProvider is the function that creates the state variables while MyContext creates the context object that holds it all. MyProvider is the all the goods, while MyContext is the box that holds them. 

**Why is context useful?**

- Context allows variables to be accessible to all decedents of the file they were defined in without having to pass them from each parent to each child on down to when they will be used.

**Can a component outside of a provider get its context?**

- Yes.

