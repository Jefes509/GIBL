<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#projets">Projets</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="accueil" class="section accueil">
        <h1>Bienvenue sur mon Portfolio</h1>
        <p>Je suis un développeur web passionné par les technologies modernes.</p>
    </section>

    <section id="projets" class="section projets">
        <h2>Mes Projets</h2>
        <div class="grid">
            <div class="project-card">
                <h3>Projet 1</h3>
                <p>Une application web de gestion de tâches avec React.</p>
            </div>
            <div class="project-card">
                <h3>Projet 2</h3>
                <p>Un site e-commerce développé avec Node.js et MongoDB.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section contact">
        <h2>Contactez-moi</h2>
        <form>
            <input type="text" placeholder="Votre nom" required>
            <input type="email" placeholder="Votre email" required>
            <textarea placeholder="Votre message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>© 2025 Mon Portfolio</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
