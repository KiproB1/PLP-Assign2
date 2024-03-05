# PLP-Assign2
HTML links
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Links</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #666;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        section {
            padding: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-gap: 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Image Links</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#gallery">Gallery</a>
    <a href="#menu">Menu</a>
</nav>

<section id="home">
    <h2>Home</h2>
    <p>Welcome to our website! Here you'll find amazing images related to different topics.</p>
    <a href="https://example.com/technology"><img src="technology.jpg" alt="Technology"></a>
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
        <a href="https://example.com/nature"><img src="nature1.jpg" alt="Nature"></a>
        <a href="https://example.com/nature"><img src="nature2.jpg" alt="Nature"></a>
        <a href="https://example.com/nature"><img src="nature3.jpg" alt="Nature"></a>
    </div>
</section>

<section id="menu">
    <h2>Menu</h2>
    <ul>
        <li><a href="https://example.com/food1"><img src="food1.jpg" alt="Food 1"> Food Item 1</a></li>
        <li><a href="https://example.com/food2"><img src="food2.jpg" alt="Food 2"> Food Item 2</a></li>
        <li><a href="https://example.com/food3"><img src="food3.jpg" alt="Food 3"> Food Item 3</a></li>
    </ul>
</section>

<footer>
    <p>&copy; 2022 Image Links</p>
</footer>

</body>
</html>
