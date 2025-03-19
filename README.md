# Introduction to JavaScript and DOM Manipulation

## Objectives

Write basic JavaScript functions.
Manipulate the DOM dynamically.
Respond to user interactions.

## Instructions

- Create a script.js file and link it to a HTML.
- Structure the document using DOCTYPE, html, head, and body.

>[!NOTE]
>  - Write JavaScript that:
>  - Changes text content dynamically.
>  - Modifies CSS styles via JavaScript.
>  - Adds or removes an element when a button is clicked.


# Tasks
- Create a well-structured HTML5 document.
- Use at least 5 different HTML elements.
- Ensure semantic correctness.```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM Manipulation Example</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <h1>Welcome to DOM Manipulation!</h1>
        <p id="paragraph">This is a paragraph that we'll change.</p>
        <button id="changeButton">Change Text</button>
        <button id="addParagraph">Add Paragraph</button>
        <ul id="myList">
            <li>Item 1</li>
            <li>Item 2</li>
        </ul>
    </div>

    <script src="script.js"></script>
</body>
</html>
```

2. CSS Styling (style.css)

```css
#container {
    width: 500px;
    margin: 50px auto;
    border: 1px solid #ccc;
    padding: 20px;
    text-align: center;
}

#paragraph {
    font-size: 18px;
    margin-bottom: 20px;
}

button {
    padding: 10px 20px;
    margin: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    cursor: pointer;
}
```

3. JavaScript (script.js)

```javascript
// Get references to elements
const paragraph = document.getElementById('paragraph');
const changeButton = document.getElementById('changeButton');
const addParagraphButton = document.getElementById('addParagraph');
const myList = document.getElementById('myList');

// Change Text Content
changeButton.addEventListener('click', () => {
    paragraph.textContent = "Text has been changed!";
});

// Add Paragraph
addParagraphButton.
- 

Happy Coding! 💻✨
