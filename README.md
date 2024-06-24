# Random Cats Gallery 🐈

This repository contains an example of a simple HTML page displaying a gallery of cat images using CSS for styling.

## Contents 🗃

##### index.html: 
The main HTML file containing the structure of the webpage.

##### styles.css: 
The CSS file containing the styles for the container, boxes, and images.

##### img/: 
Directory containing the images used in the webpage.

➡
To view the cat gallery, open the index.html file in a web browser. Ensure that the images and CSS file are in the correct directories as specified.

## Files 📁
##### -index.html
This file contains the HTML structure for the webpage, including three boxes each containing three images, and a header.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diseño con imagenes</title>
    <link rel=stylesheet type="text/css" href="styles.css">
</head>

<body>
    <div class="container">
        <div class="box box1">
            <img src="img/adventure-cat.png" alt="imagen1" class="image">
            <img src="img/zeldacat.jpg" alt="imagen2" class="image">
            <img src="img/topguntocat.png" alt="imagen3" class="image">
        </div>

        <div class="box box2">
            <img src="img/spidertocat.png" alt="imagen4" class="image">
            <img src="img/daftpunktocat-guy.gif" alt="imagen5" class="image">
            <img src="img/nyantocat.gif" alt="imagen6" class="image">
        </div>

        <div class="box box3">
            <img src="img/ironcat.jpg" alt="imagen7" class="image">
            <img src="img/murakamicat.png" alt="imagen8" class="image">
            <img src="img/okal-eltocat.jpg" alt="imagen9" class="image">
        </div>

        <div class="box4">
            <h3> Random Cats</h3>
        </div>
    </div>
</body>

</html>
```

##### -styles.css
This file contains the CSS styles for the container, boxes, images, and header. It sets the background colors, sizes, and positioning of the elements.

```css
.container {
    background-color: rgb(255, 255, 255);
    width: 1000px;
    height: auto;
    margin: 0 auto;
    padding: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.box {
    width: 1000px;
    height: 200px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.box1 {
    background-color: rgb(24, 23, 23);
}

.box2 {
    background-color: rgb(53, 52, 51);
}

.box3 {
    background-color: rgb(77, 78, 78);
}

.box4 {
    background-color: rgba(19, 148, 7, 0.815);
    width: 1000px;
    height: 40px;
}

.image {
    width: 180px;
    height: 180px;
}

h3 {
    color: aliceblue;
    font-family: monospace;
    margin-left: 430px;
    font-size: 15px;
}
```
### Directory Structure
Ensure the following directory structure for the files:

```css
project-root/
├── index.html
├── styles.css
└── img/
    ├── adventure-cat.png
    ├── zeldacat.jpg
    ├── topguntocat.png
    ├── spidertocat.png
    ├── daftpunktocat-guy.gif
    ├── nyantocat.gif
    ├── ironcat.jpg
    ├── murakamicat.png
    └── okal-eltocat.jpg

```