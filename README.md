<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Se connecter</title>
</head>
<body>
    <h2>Se connecter à votre compte</h2>
    <form action="/login" method="POST">
        <label for="username">Nom d'utilisateur</label>
        <input type="text" id="username" name="username" required>
        <br>
        <label for="password">Mot de passe</label>
        <input type="password" id="password" name="password" required>
        <br>
        <button type="submit">Se connecter</button>
    </form>
</body>
</html>
