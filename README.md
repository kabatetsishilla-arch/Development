# Development
website development using java script
Yes. You can develop a website using JavaScript together with HTML and CSS.

Think of them like this:

HTML → creates the structure/content of the website.
CSS → makes the website look attractive.
JavaScript → makes the website interactive and responsive to the user.
1. Create your project folder

For example:

MyWebsite/
│
├── index.html
├── style.css
└── script.js
2. Create the HTML file

index.html

<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <h1>Welcome to My Website</h1>

    <p id="message">Click the button below.</p>

    <button onclick="changeMessage()">Click Me</button>

    <script src="script.js"></script>
</body>
</html>
3. Add CSS

style.css

body {
    font-family: Arial;
    text-align: center;
    background-color: lightblue;
    padding: 50px;
}

button {
    padding: 10px 20px;
    background-color: navy;
    color: white;
    border: none;
    cursor: pointer;
}
4. Add JavaScript

script.js

function changeMessage() {
    document.getElementById("message").innerHTML =
        "Hello! JavaScript is working!";
}
5. How the JavaScript works

When you click Click Me:

function changeMessage()

creates a function called changeMessage.

Then:

document.getElementById("message")

finds the paragraph with the ID message.

Finally:

.innerHTML = "Hello! JavaScript is working!";

changes the text inside that paragraph.

What JavaScript can do on a website

JavaScript can be used to:

Create buttons and interactive menus.
Validate forms.
Create image sliders.
Make calculators.
Display dates and times.
Show and hide information.
Create animations.
Connect a website to a database/server.
Create shopping carts.
Build interactive websites and web applications.

Simple way to remember:

HTML = Structure
CSS = Appearance
JavaScript = Action/Behavior
