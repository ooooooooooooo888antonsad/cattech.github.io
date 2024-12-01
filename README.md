<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3D Druck Bestellungen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }
        header img {
            max-width: 150px; /* Größe des Logos anpassen */
            margin-bottom: 10px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"], input[type="email"], textarea {
            margin-bottom: 10px;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        textarea {
            resize: vertical;
        }
        button {
            padding: 10px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

<header>
    <img src="logo.jpg" alt="CAT tech Logo"> <!-- Dein Logo im .jpg Format -->
    <h1>3D Druck Bestellungen</h1>
</header>

<div class="container">
    <h2>Bestelle 3D-druckbare Objekte</h2>
    <form action="mailto:antoschasad@gmail.com" method="post" enctype="text/plain">
        <label for="name">Dein Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Deine E-Mail-Adresse:</label>
        <input type="email" id="email" name="email" required>

        <label for="item">Bestelltes Objekt:</label>
        <input type="text" id="item" name="item" required>

        <label for="details">Weitere Details:</label>
        <textarea id="details" name="details" rows="4"></textarea>

        <button type="submit">Bestellen</button>
    </form>
</div>

</body>
</html>
