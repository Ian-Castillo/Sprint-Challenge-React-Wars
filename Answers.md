# Answers

1. What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.

React JS is a JavaScript library for building user interfaces. Websites like Quora, Twitter and Facebook have users clicking all over the webpages and React allows things to run smoothly in the virtual DOM. 
    
Per Lambda TK this paragraphs summarizes it pretty concisely. 
    
 “In a process called “reconciliation”, React will detect that the state of the app has changed. Then it will update the virtual DOM, taking note of which nodes have changed due to the state changes. Finally, once it knows which nodes have changed, it will update only those specific nodes on the actual DOM. This takes a lot of pressure off of our browsers and it’s why React is as powerful as it is.”

1. What does it mean to think in react?

React is a pattern, a mindset, that will help developers that use it, build small, reusable pieces of UI that can be easily put together to make a large scale application.

1. Describe state.

State is an object that determines how that component renders & behaves. In other words, “state” is what allows you to create components that are dynamic and interactive. 

1. Describe props.

Props are the values that are passed in to components to be processed (aka displayed, used to decided something, etc) inside the component.

1. What are side effects, and how do you sync effects in a React component to state or prop changes?

A side effect is anything that affects something outside the scope of the function being executed. Fetching data from an API, timers, logging, and manually manipulating the DOM are all examples of side effects.