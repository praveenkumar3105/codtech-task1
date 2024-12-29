NAME:M PRAVEENKUMAR
Project Name: To-Do List Web Application

Description:
The project I am working on is a simple To-Do List Web Application, which allows users to add and delete tasks. It uses basic front-end technologies such as HTML, CSS, and JavaScript to create a user-friendly and interactive application.

Explanation of the Code:

1. HTML Structure:

The <!DOCTYPE html> declaration defines the document type and version.

The html element with the lang="en" attribute sets the language of the document to English.

The head section contains meta tags for character set and viewport settings, and a title tag that names the application.

The body contains a div with the class container to hold all the content. Inside the container, there’s a heading (<h1>) for the title "To-Do List", a form for adding tasks, and an unordered list (<ul>) for displaying the tasks.

The form contains an input field for entering tasks and a button to submit the form.

The list (<ul>) will dynamically display the tasks added by the user.



2. CSS Styling:

The styles define the appearance of the application, such as the background color, text styling, and the layout of elements.

The body uses flexbox to center the content vertically and horizontally on the page.

The container has a white background with padding, rounded corners, and a box shadow to create a card-like effect.

Input and button elements are styled for clarity and ease of use. The button has a hover effect to indicate interactivity.

The task list is styled to look clean, with each task in a separate li element. The delete button is red, and it changes color when hovered.



3. JavaScript Functionality:

JavaScript is used to add interactivity to the application.

When the form is submitted, an event listener triggers the creation of a new task item.

The task text is extracted from the input field, and if the input is not empty, a new list item (<li>) is created with the task text and a delete button.

The new task item is appended to the unordered list (<ul>).

After adding the task, the input field is cleared.

The delete button has an event listener that removes the task when clicked.




This project demonstrates how to build a functional, interactive To-Do list application using only HTML, CSS, and JavaScript. The focus was on creating a simple, intuitive user interface and adding basic functionality to manage tasks
