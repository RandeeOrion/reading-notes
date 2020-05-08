# Event Driven Applications

**Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?**

- A request from the client: an api or db

**Why are events sometimes better than asynchronous actions with callbacks?**

- Multiple callbacks can get gross and confusing. Event listeners can have multiple actions happening without getting too convoluted.

**What does an EventEmitter instance do?**

- We can remove or add listeners and trigger events 

**When is a program’s call stack, event queue, and event loop active?**

- Whenever the events are triggered. 