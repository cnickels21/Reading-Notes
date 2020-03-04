# Reading Journal 06

## Object Literals

By all technical terms, everything within code is an object. The object literal is a code block that allows you to store key value pairs inside curly braces, and you separate each key value pair using a comma. For example the variable 'chase' = \{name: chase\} would return as an object as opposed to a string. You can also store just about anything inside of an object. If you place a function inside of an object it is known as a method. Object literals are useful when you have to store a lot of information pertaining to a single object that you will be calling into your document later using different methods. We will talk about this when we cover the domain object model. You can also use the key value pairs in your object to run calculations and return output accordingly. The object literal is an efficient way to store information that can be used in many different ways throughout your document.

## The Domain Object Model

As we know, everything in HTML is treated as a block inside of your web page \(with the except of inline elements of course\). The Document object model, or DOM, allows you to access each one of these blocks on your page in different ways. It is laid out similar to a family tree with children elements inside of their parent elements and so on. Within this tree are different types of nodes. There are document nodes, element nodes, attribute nodes, and text nodes. There are many ways to access and modify the content of your page using JS and the DOM. You can call elements by their id or class name, using their tags specifically, or even using css selectors. In order to accomplish this there is a multitude of methods at your disposal; getElementById or Class, querySelector, textContent, innerHTML, and innerText are a few examples of these methods and some are more popular than others depending on what you are attempting to do. There are also methods to access a specific child within an element such as firstChild, lastChild, or even previous and next sibling. Working with the DOM is a clever and efficient way to access the different parts of your page using JavaScript to customize your page based on user interactivity. An example of this would be changing the color of a button when the user clicks it by changing its class or id accordingly \(this would be an example of an event listener that we will get into later\).