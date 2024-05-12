jQuery Cheat Sheet:

1. Selectors:

   - $(selector) - Selects elements based on the given selector.
   - $(element) - Wraps the given DOM element into a jQuery object.

2. DOM Manipulation:

   - .html(content) - Sets or gets the HTML content of an element.
   - .text(content) - Sets or gets the text content of an element.
   - .val(value) - Sets or gets the value of an input element.
   - .addClass(class) - Adds the specified class to the selected elements.
   - .removeClass(class) - Removes the specified class from the selected elements.
   - .toggleClass(class) - Toggles the specified class on the selected elements.

3. Event Handling:

   - .click(handler) - Attaches a click event handler to the selected elements.
   - .on(event, handler) - Attaches an event handler to the selected elements.
   - .off(event, handler) - Removes an event handler from the selected elements.

4. Animation:

   - .show() - Shows the selected elements with a sliding motion.
   - .hide() - Hides the selected elements with a sliding motion.
   - .fadeIn() - Fades in the selected elements.
   - .fadeOut() - Fades out the selected elements.
   - .slideUp() - Slides up the selected elements.
   - .slideDown() - Slides down the selected elements.

5. AJAX:

   - .load(url, data, callback) - Loads data from a server and inserts it into the selected elements.
   - .get(url, data, success, dataType) - Sends an HTTP GET request to the server.
   - .post(url, data, success, dataType) - Sends an HTTP POST request to the server.

6. Effects:

   - .addClass(class, duration, easing, callback) - Adds the specified class to the selected elements with animation.
   - .removeClass(class, duration, easing, callback) - Removes the specified class from the selected elements with animation.
   - .animate(styles, duration, easing, callback) - Animates the selected elements with custom CSS properties.

7. Utility Functions:
   - $.each(array, callback) - Iterates over an array or object.
   - $.ajax(options) - Performs an asynchronous HTTP request.
   - $.trim(string) - Removes leading and trailing whitespaces from a string.

Remember to include the jQuery library in your HTML file before using any jQuery functions:

<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
