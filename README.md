# drag-and-drop
Drag and Drop is a common feature in web applications that allows users to click and drag an element from one place and drop it somewhere else.
Project: Drag-and-Drop Functionality
1. Project Overview
This project demonstrates the implementation of drag-and-drop functionality using HTML, CSS, and JavaScript. It allows elements to be dragged from one container (box) and dropped into another. The boxes can be any container element on the page, and the content can be moved around freely.

2. Technologies Used
HTML: Structure of the webpage.
CSS: Styling the containers and elements.
JavaScript: Handling the drag-and-drop functionality.

3. Files Overview
index.html: Contains the HTML structure of the page.
style.css: Styles the boxes and list items, providing visual feedback for the drag-and-drop.
script.js: Contains the JavaScript logic for handling drag and drop operations.

4. Basic HTML Structure
The HTML structure involves:

Two boxes (left and right) where draggable items are placed.
A list of items that can be dragged between these two boxes.

5. JavaScript Logic
JavaScript is responsible for the functionality of drag and drop:

Drag Start: When a list item is dragged, we capture the dragged element.
Drag Over: To allow the element to be dropped, we must prevent the default behavior of the event.
Drop: When the item is dropped, it moves to the target container.

6. Key Concepts Used
draggable="true": HTML5 attribute that allows an element to be dragged.
dragstart: JavaScript event triggered when dragging starts. We store the dragged element in the selected variable.
dragover: Event triggered when an element is dragged over a valid drop target. We prevent the default behavior to allow dropping.
drop: Event triggered when an element is dropped into a valid drop target. We append the dragged element to the target container.
