# Class14_HTML_CSS_JS
A simple project demonstrating the integration of HTML, CSS, and JavaScript in a webpage. Includes a text paragraph, styled content, alert messages, button interaction, and an example of a deceptive hyperlink (for cybersecurity awareness).
# Class 14 - HTML, CSS, and JavaScript Example

This project is a **Class 14 assignment** that demonstrates the use of HTML, CSS, and JavaScript in a single webpage.  
It covers:

- Linking an external CSS file
- Using inline and internal JavaScript
- Displaying alert messages
- Adding interactive buttons
- Demonstrating a cybersecurity example of a fake hyperlink

---

## Features

- **HTML Structure** with headings, paragraphs, and buttons
- **CSS File** (`class 14.css`) linked externally for styling
- **JavaScript Alerts** to welcome users and show messages when a button is clicked
- **Cybersecurity Task:** A fake link that appears to be `https://facebook.com` but actually points to `http://hacker.com`

---

## Example Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 14</title>
    <link rel="stylesheet" href="class 14.css">
    <script>
        alert("Welcome to my webpage")
    </script>
    <script>
        function showMessage() {
            alert("Hello!");
        }
    </script>
</head>
<body>
    <h1>My Task:</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
    <br>
    <button onclick="showMessage()">click me</button>
    <br><br>
    <h3>Cybersecurity Task:</h3>
    <p style="color: rgb(3, 2, 51);">
        Create a link that looks like https://facebook.com but actually points to http://hacker.com.
    </p>
    <a href="https://hacker.com" target="_blank">https://facebook.com</a>
</body>
</html>
