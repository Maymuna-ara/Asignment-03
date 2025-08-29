1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans:
getElementById → This is used to find one element by its ID. Since ID is unique, it always gives one element.
getElementsByClassName → This finds elements by a class name. It can return many elements as a list.
querySelector → This uses CSS selector to find an element, but it only returns the first match.
querySelectorAll → This also uses CSS selector, but it returns all matching elements in a list

short Overview:
ID = single element
Class = multiple elements
querySelector = first match by CSS style
querySelectorAll = all matches by CSS style



2.How do you create and insert a new element into the DOM?
Ans:
To add a new element in the page, first we make it using document.createElement().
After that, we can put some text or set an attribute to it.
Finally, we add it inside another element (like body or a div) by using appendChild() or append().

Example:
let newDiv = document.createElement("div");
newDiv.innerText = "This is a new element";
document.body.appendChild(newDiv);

Here, a new < div> is created, text is added, and then it is placed inside the body of the page.



3.What is Event Bubbling and how does it work?
Ans:
Event bubbling means when an event happens on a child element, it doesn’t stop there. The event goes up step by step to its parent, then to the grandparent, and so on.
Example:
If you click a button → the click goes first to the button, then to the parent div, then to the body.
That’s how bubbling works (from inside to outside).



4.What is Event Delegation in JavaScript? Why is it useful?
Ans:
Event delegation means putting an event listener on a parent element, and then handling the events of its child elements from there.
Example:
If you have many buttons, instead of adding one listener for each button, you can add one listener to their parent div. When any child button is clicked, you can detect it using event.target.
This is useful because it reduces code, makes the site faster, and still works even if new child elements are added later.

5.What is the difference between preventDefault() and stopPropagation() methods?
Ans:
preventDefault() → Stops the default action of an element.
Example: 
when you submit a form, the page normally reloads. If you use this, the reload will not happen.

stopPropagation() → Stops the event from moving up in bubbling.
Example:
 if you click a button inside a div, normally both button and div get the event. With this, only the button gets it.

Summary:
preventDefault() = stops the default action
stopPropagation() = stops the event from going up