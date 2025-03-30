# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
______________________________________________________________________________________________________________________________________________________________________________________________________________________________


 ---index.html---


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Introduction</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1 class="title">Welcome to CSS Styling</h1>
    </header>
    
   <section>
        <p id="intro">CSS allows us to style HTML elements beautifully.</p>
        <img src="image.jpg" alt="Example Image" class="styled-image">
    </section>
    
   <footer>
        <p>© 2025 Web Development</p>
   </footer>
</body>
</html>


_______________________________________________________________________________________________________________________________________________________________________________________________________________________________


---style.css---



/* Apply styles using different selectors */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
    text-align: center;
    margin: 20px;
}

/* Class selector */
.title {
    color: #007BFF;
    font-size: 2rem;
    margin-bottom: 15px;
}

/* ID selector */
#intro {
    font-style: italic;
    color: #555;
    padding: 10px;
    border: 1px solid #ccc;
}

/* Image styling */
.styled-image {
    width: 300px;
    border-radius: 10px;
    border: 3px solid #333;
    margin-top: 10px;
}



_____________________________________________________________________________________________________________________________________________________________________________________________________________________________
