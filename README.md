<!DOCTYPE html>
<html lang="lv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>12. nedēļa</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>12. nedēļa</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Mājas</a></li>
            <li><a href="#about">Par mums</a></li>
            <li><a href="#services">Pak services</a></li>
            <li><a href="#contact">Kontakti</a></li>
        </ul>
    </nav>
    <div id="main-container">
        <div id="side-content">
            <h2>Par mums</h2>
            <p>Šī ir īsa informācija par mūsu organizāciju.</p>
        </div>
        <div id="photo-container">
            <img src="image1.jpg" alt="Attēls 1">
            <img src="image2.jpg" alt="Attēls 2">
            <img src="image3.jpg" alt="Attēls 3">
            <img src="image4.jpg" alt="Attēls 4">
        </div>
    </div>
</body>
</html>
style.css:
css
Kopēt kodu
/* Vispārīgie stili */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style-type: none;
    padding: 0;
    text-align: center;
    background-color: #333;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

#main-container {
    display: flex;
    padding: 20px;
}

#side-content {
    width: 30%;
    padding: 20px;
    background-color: #f4f4f4;
}

#photo-container {
    display: grid;
    width: 70%;
    padding: 20px;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
}

#photo-container img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

h1, h2 {
    margin: 0;
    font-size: 2em;
}

p {
    font-size: 1.1em;
}
