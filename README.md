
The DOM is like a tree:

Root: <html>
Children: <head>, <body>
Inside: <div>, <p>, <h1>, etc.

Each node can be accessed and modified using JavaScript.

4. Accessing Elements
document.getElementById("id")
document.getElementsByTagName("tag")
document.getElementsByClassName("class")
document.querySelector("selector")
document.querySelectorAll("selector")

5. Changing Content
document.getElementById("demo").innerHTML = "Hello DOM!";

6. Changing Attributes
document.getElementById("image").setAttribute("src", "newimage.jpg");

7. Changing CSS
document.getElementById("demo").style.color = "blue";

8. Add / Remove Elements
const newPara = document.createElement("p");
document.body.appendChild(newPara);

document.getElementById("demo").remove();

9. Event Handling
button.addEventListener("click", function() {
  alert("Button clicked!");
});

10. To-Do List Example
A simple app that adds and removes tasks using DOM manipulation.

11. Summary
DOM is a tree structure of a web page
JavaScript manipulates DOM to update content
DOM makes web pages interactive

12. References
https://www.w3schools.com/js/js_htmldom.asp
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model