# Routing and Components 

**Why do we not need more .html pages in a multi-page React app?**
- The BrowserRouter and Route allow us to effectively write switch statements, changing what is rendered to the page and moving through endpoints. 

**If we wanted a component to show up on every page, where would we put it and why?**
- Outside the <BrowserRouter/> because inside the browser router is where we put all the routes that we switch out 


**What does props.children contain?**
- Data that is passed from the content currently being rendered to the 'dumb' component it is being rendered in. 