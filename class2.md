# Classes, Inheritance, Function

**What is one benefit of JavaScript not enforcing type?**
_Maintenance of code becomes easier. If types of variables, for instance, change, a developer does not need to go back into the code where that variable was created and change the type declared._

**What is one downside of JavaScript not enforcing type?**
_If the type is not enforced, data can come back to you in a form you weren't expecting and break the code. Type of must then be checked._

**Should the parameters of a function be changed when the function returns? Why or why not?**
_The parameters of a function should not change when the function returns. A pure function does one thing and only one thing. If functions start doing many things, data can get muddied and mixed up._

**Describe a type of data that has rules,aside from the given examples of Number, Integer and Float. What are the rules the data should follow?**

_'const' variables, while are not immutable, do create a less flexible variable. For example, an array set as const can only ever be an array. A function set as a const variable can only ever be a function, and thus becomes harder to reassign later._
