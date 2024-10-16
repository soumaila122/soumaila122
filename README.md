<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soumaïla Service Digital</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .hero {
            background: url('votre-image.jpg') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .services, .about, .contact {
            padding: 20px;
            text-align: center;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Soumaïla Service Digital</h1>
    <nav>
        <a href="#services">Nos services</a>
        <a href="#about">À propos</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero">
    <h2>Boostez votre business avec nos solutions de QR code !</h2>
    <button><a href="#contact" style="color: white; text-decoration: none;">Commencez maintenant</a></button>
</div>

<section id="services" class="services">
    <h2>Nos services</h2>
    <p>Nous offrons des solutions de QR code adaptées à vos besoins.</p>
    <ul>
        <li>Création de codes QR</li>
        <li>Gestion et suivi des QR codes</li>
        <li>Consultation et optimisation</li>
    </ul>
</section>

<section id="about" class="about">
    <h2>À propos de nous</h2>
    <p>Soumaïla Service Digital est dédié à vous aider à tirer parti de la technologie moderne.</p>
</section>

<section id="contact" class="contact">
    <h2>Contactez-nous</h2>
    <form>
        <label for="name">Nom :</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email :</label><br>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Message :</label><br>
        <textarea id="message" name="message" required></textarea><br>
        <input type="submit" value="Envoyer">
    </form>
</section>

<footer>
    <p>&copy; 2024 Soumaïla Service Digital. Tous droits réservés.</p>
</footer>

</body>
</html>
