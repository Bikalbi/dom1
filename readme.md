## Description
This project demonstrates how to manipulate a `div` element in an HTML document using JavaScript. It dynamically applies styles and content to the element with the `id` of `box`.

## Features
- Dynamically sets the dimensions, background color, margin, and padding of the `div` element.
- Adds styled text content to the `div`.
- Simple HTML and JavaScript integration.

## Files
- **index.html**: The HTML structure of the project.
- **indx.js**: The JavaScript file containing the code to style and update the `div`.

## Code Explanation
### HTML (index.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div id="box">
        
    </div>
    <script src="./indx.js"></script>
</body>
</html>
```
This file sets up the HTML document with a `div` element having an `id` of `box`. The JavaScript code is linked via the `<script>` tag.

### JavaScript (indx.js):
```javascript
let div = document.getElementById("box");
div.style.width = "300px";
div.style.height = "200px";
div.style.backgroundColor = "yellow";
div.style.margin = "20px";
div.style.padding = "10px";
div.innerText = "Hello, I am div!";
div.style.color = "blue";
div.style.fontSize = "18px";
div.style.fontWeight = "bold";
```
This script selects the `div` element and applies the following styles and properties:
- **Width and Height**: Sets the dimensions to 300px by 200px.
- **Background Color**: Changes the background color to yellow.
- **Margin and Padding**: Adds spacing around and inside the `div`.
- **Text Content**: Adds the text "Hello, I am div!" inside the `div`.
- **Text Styles**: Sets the font color to blue, font size to 18px, and font weight to bold.

## How to Run
1. Clone the repository or download the files.
2. Open the `index.html` file in any modern web browser.
3. The styled `div` with text will be displayed on the page.



