<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Linktree Simile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .container {
            text-align: center;
            background: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 90%;
            max-width: 400px;
        }

        .profile-img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
        }

        .profile-name {
            margin: 10px 0 5px;
            font-size: 24px;
        }

        .profile-description {
            margin: 0;
            color: #666;
            font-size: 14px;
        }

        .links {
            margin-top: 20px;
        }

        .link {
            display: block;
            padding: 10px 0;
            margin: 10px 0;
            background: #0073e6;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .link:hover {
            background: #005bb5;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <img src="profile.jpg" alt="Profilo" class="profile-img">
            <h1 class="profile-name">Nome Utente</h1>
            <p class="profile-description">Breve descrizione dell'utente</p>
        </div>
        <div class="links">
            <a href="https://example.com" class="link">Link 1</a>
            <a href="https://example.com" class="link">Link 2</a>
            <a href="https://example.com" class="link">Link 3</a>
            <a href="https://example.com" class="link">Link 4</a>
        </div>
    </div>
</body>
</html>
