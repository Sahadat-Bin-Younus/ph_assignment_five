 Repository Link : https://github.com/Sahadat-Bin-Younus/ph_assignment_five.git
 Live Site Link : https://sahadat-bin-younus.github.io/ph_assignment_five/

5 question's answer:

1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

answer:
getElementById: returns a single element by its unique id.
getElementsByClassName: Returns all elements with a given class as an HTML collection.
querySelector: Returns the first element when matching a CSS selector.
querySelectorAll: Returns all elements when matching a selector as a Node list.

2.How to create and insert a new element into the DOM?

answer:
const newDiv = document.createElement("div");
newDiv.textContent = "Hi";
document.body.appendChild(newDiv);

3.What is Event Bubbling?
answer:

When an event occurs on a child element, it is first handled by that element, then passed (bubbles up) to its parent elements, continuing until the root.
for example: 
Clicking a button inside a div triggers the button’s event first, then the div’s, then the body’s.

4.What is Event Delegation in JavaScript? Why is it useful?
answer:

Event delegation means attaching a single event listener to a parent element to handle events from its child elements using bubbling.
it is useful for handling dynamic elements, Reduces memory usage and for Cleaner code.

5.What is the difference between preventDefault() and stopPropagation() methods?
answer:

preventDefault() means : Stops the browser’s default behavior (e.g., form submission, link navigation).
stopPropagation() means : Stops the event from bubbling up to parent elements.



