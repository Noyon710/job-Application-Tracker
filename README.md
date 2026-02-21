

1. Difference between getElementById, getElementsByClassName, querySelector / querySelectorAll

Ans : 
getElementById is used to select one element by its id.

getElementsByClassName is used to select multiple elements that have the same class name.

querySelector selects the first element that matches a CSS selector.

querySelectorAll selects all elements that match a CSS selector.



2. How do you create and insert a new element into the DOM?

Ans:
First, we create a new element using createElement.
Then we add text or other content to it.
After that, we insert it into a parent element using appendChild.



3. What is Event Bubbling?

Ans:
Event Bubbling means when an event happens on an element, it first runs on that element and then moves up to its parent elements.



4. What is Event Delegation? Why is it useful?

Ans:
Event Delegation means adding an event listener to a parent element to handle events of its child elements.

It is useful because it reduces the number of event listeners and works for dynamically added elements.



 5. Difference between preventDefault() and stopPropagation()

Ans:
preventDefault() stops the default action of the browser.

stopPropagation() stops the event from moving to parent elements.

