Interview questions

How to validate form inputs in JavaScript? You use JavaScript to listen for the form’s submit event, then check each input field’s value. If a field is empty or doesn’t meet your criteria (like email format), you show an error message and prevent the form from submitting.

What is event.preventDefault()? It’s a method that stops the browser from doing its default action. For example, when a form is submitted, it usually reloads the page. Using event.preventDefault() lets you handle the submission with JavaScript instead.

How to check email format with regex? You use a regular expression (regex) pattern to test the email string. A common one is /^[^\s@]+@[^\s@]+\.[^\s@]+$/, which checks for a basic valid email structure like name@example.com.

Difference between client-side and server-side validation? Client-side validation happens in the browser using JavaScript—it’s fast and gives instant feedback. Server-side validation happens on the backend and is more secure because it doesn’t rely on the user’s browser. You should always use both.

How to show error messages dynamically? You target specific elements in the DOM (like <small> tags under inputs) and update their text content with error messages when validation fails. You can also style them with CSS to make them stand out.

What is form submission? It’s the process of sending form data to a server or handling it with JavaScript. In this task, we simulate submission by showing a success message instead of actually sending data.

How to improve form accessibility? Use proper labels linked to inputs with for and id. Make sure the form is keyboard-friendly, use ARIA attributes if needed, and provide clear error messages that screen readers can detect.

How to handle form reset? You can use form.reset() in JavaScript to clear all input fields and return the form to its initial state. It’s useful after a successful submission or if the user wants to start over.

What are common security issues with forms? Forms can be vulnerable to attacks like XSS (cross-site scripting), CSRF (cross-site request forgery), and SQL injection. Always sanitize inputs, validate on the server, and use secure coding practices.

How does HTML5 built-in validation differ from JS validation? HTML5 uses attributes like required, type="email", and pattern to validate inputs automatically. JavaScript validation gives you more control—you can customize error messages, add complex logic, and handle edge cases better.