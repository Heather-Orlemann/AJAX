# Archived Repository for AJAX
AJAX Assignment Repository

This repository contains a simple AJAX (Asynchronous JavaScript and XML) assignment to demonstrate the basic concepts of AJAX and how it is used to perform asynchronous requests to dynamically update web content without reloading the page.

Overview

In this assignment, we will create a basic HTML page with a button that, when clicked, fetches content from another HTML file and updates the page without a full reload. This is achieved using AJAX and the XMLHttpRequest object to perform an asynchronous request.

Getting Started

To begin, clone this repository to your local machine or download the provided files. You will find two files in the repository:

ajax_basic.html - The main HTML file that contains the AJAX implementation and user interface.
content.html - The HTML file containing the content that will be fetched and displayed on the main page when the button is clicked.
Usage
Open ajax_basic.html in your web browser. You should see a "Get Content" button. When you click this button, the content from the content.html file will be fetched and displayed on the page without a full page reload.

How it Works

The ajax_basic.html file contains JavaScript code that creates a new XMLHttpRequest object, sets up the request, and defines a callback function using the onreadystatechange property. This callback function checks if the request is complete and if the response data is available. If the conditions are met, the content of the main page is updated with the response data from the content.html file.

Feel free to explore this repository and use it as a starting point for your own AJAX projects. Happy coding!
