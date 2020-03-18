# Weather_Dashboard

Comments discussing the purpose of most lines of code are provided in the index.html and the script.js files.

Note:  I added in error management for the AJAX call in function searchWeather().  This was done by adding an 'error:' statement and a function to execute in case of an error, after the 'success:' block.  HTML code for a modal was added to index.html, with id="myModal" assigned to the first 'div'.  When an error occurs (no input or unrecognized input), the function captures the type and description of the error in a variable, adds the text in that variable to the modal title div, then opens the modal with the jQuery modal(function).  I had to add the additional script tags at the bottom of index.html to include additional jQuery and javascript functionality.