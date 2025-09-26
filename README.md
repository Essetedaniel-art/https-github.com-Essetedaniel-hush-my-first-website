# https-github.com-Essetedaniel-hush-my-first-website
My-first-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Simple Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to My Simple Website!</h1>
    <p>This is a demo site inside the <code>website/</code> folder. You can add more content and files as you grow your project!</p>
    <img src="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80" alt="Sample image" width="300">
    <br>
    <a href="https://www.example.com" target="_blank">Visit Example Website</a>
</body>
</html>
body {
    background-color: #f9fafb;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    margin: 30px;
    padding: 15px;
}

h1 {
    color: #0074D9;
    font-size: 2.2em;
    margin-bottom: 18px;
}

p {
    color: #222;
    font-size: 1.1em;
    padding: 8px;
    background: #e3eefa;
    border-radius: 7px;
    margin-bottom: 15px;
}

img {
    border-radius: 10px;
    margin-bottom: 12px;
}

a {
    display: inline-block;
    color: #fff;
    background: #0074D9;
    text-decoration: none;
    padding: 8px 18px;
    border-radius: 5px;
    font-weight: bold;
    margin-top: 8px;
    transition: background 0.3s;
}

a:hover {
    background: #005fa3;
}
