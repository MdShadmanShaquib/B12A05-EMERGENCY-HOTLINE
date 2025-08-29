1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
Answer: getElementById selects elements uniquely and specificly by it's id.
        getElementsByClassName selects the elements by their class and give array like object
        querySelector gives you first child of the specified class
        querySelectorAll gives you all child of the specified class and we can write it like css

2. How do you **create and insert a new element into the DOM**?
Answer: const newElement = document.createElement("p");
        parentElement.appenChild(newElement);

3. What is **Event Bubbling** and how does it work?
Answer: bubbling means event triggered from child to parent continuouely to stop it use event.propagation();

4. What is **Event Delegation** in JavaScript? Why is it useful?
Answer: by using event bubbling we can use event listener in multiple child. it's useful cz it needs less work  and dynamic also
5. What is the difference between **preventDefault() and stopPropagation()** methods?
Answer: preventDefault() prevents default behavior of browser and 
        stopPropagation() stops event bubbling.




