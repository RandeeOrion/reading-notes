**What is a benefit to using express.Router()?**
an express.Router can be modularized 

**When I say that top-down order matters in Express, what does that mean?**
File is read top to bottom, but also executed from top to bottom, rather than when a function is called. 

**Why do we use a model class (with create(), read(), etc.) instead of directly calling MongoDB operations (such as save(), find(), etc.) within our Express route handlers?**
This creates an interface that is more generic and user friendly. If a database was going to be changed to a different type of software, not all the code would have to be updated, just the code inside the CRUD functions. 
