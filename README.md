<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Business</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Business</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="gallery.html">Gallery</a>
        </nav>
    </header>

    <section class="content">
        <h2>About Us</h2>
        <p>This is a simple business website showcasing our products and services.</p>
    </section>

    <footer>
        <p>Follow us on:</p>
        <a href="#">Facebook</a> | <a href="#">Instagram</a> | <a href="#">Twitter</a>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - My Business</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Gallery</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="gallery.html">Gallery</a>
        </nav>
    </header>

    <section class="gallery">
        <img src="https://via.placeholder.com/200" alt="Image 1">
        <img src="https://via.placeholder.com/200" alt="Image 2">
        <img src="https://via.placeholder.com/200" alt="Image 3">
    </section>

    <footer>
        <p>Follow us on:</p>
        <a href="#">Facebook</a> | <a href="#">Instagram</a> | <a href="#">Twitter</a>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: white;
    color: black;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background-color: green;
    color: white;
    padding: 10px;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
}

.gallery img {
    width: 200px;
    height: 150px;
    margin: 10px;
    border: 2px solid red;
}

footer {
    background-color: red;
    color: white;
    padding: 10px;
    position: absolute;
    width: 100%;
    bottom: 0;
}