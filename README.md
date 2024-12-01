# Portfolio-MFE.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio de Maxime Farfan Escobar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            animation: fadeIn 2s ease-in-out;
        }

        header {
            background-color: #2f6f4e; /* Vert nature */
            color: white;
            padding: 1em 0;
            text-align: center;
            animation: slideIn 1s ease-out;
        }

        section {
            padding: 2em;
            margin: 2em auto;
            max-width: 900px;
            background-color: white;
            border-radius: 8px;
            opacity: 0;
            animation: fadeInUp 1.5s forwards;
        }

        h2 {
            color: #2f6f4e;
        }

        .skills, .experience, .contact, .about, .education {
            margin-bottom: 2em;
        }

        footer {
            background-color: #2f6f4e;
            color: white;
            text-align: center;
            padding: 1em 0;
        }

        a {
            color: #2f6f4e;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #1e4d37;
        }

        .contact-info {
            font-size: 1.2em;
        }

        .education-info, .work-info {
            margin-bottom: 1em;
        }

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideIn {
            0% { transform: translateY(-50px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

    </style>
</head>
<body>

<header>
    <h1>Portfolio de Maxime Farfan Escobar</h1>
</header>

<section class="about">
    <h2>À propos de moi</h2>
    <p>Bonjour, je m'appelle Maxime Farfan Escobar. Passionné par le commerce et la nature, j'ai une formation en Techniques de Commercialisation (DUT) et une expérience professionnelle variée dans des secteurs comme le retail (chez Decathlon), le jardinage et les produits innovants (stage chez Birdie). Je suis une personne polyvalente, investie et à l'écoute, prête à relever de nouveaux défis.</p>
</section>

<section class="skills">
    <h2>Compétences</h2>
    <ul>
        <li>Polyvalent et à l'écoute</li>
        <li>Expérience en gestion de projets et développement de produits</li>
        <li>Compétences en communication et en vente</li>
        <li>Connaissances en marketing et techniques commerciales</li>
        <li>Expérience en gestion de stock et en retail</li>
    </ul>
</section>

<section class="education">
    <h2>Éducation</h2>
    <div class="education-info">
        <h3>Bac Économie et Social</h3>
        <p>Obtenu avec mention Assez Bien. Formation axée sur l'économie, la gestion et les sciences sociales.</p>
    </div>
    <div class="education-info">
        <h3>DUT Techniques de Commercialisation</h3>
        <p>Formation professionnelle centrée sur le marketing, la vente et la gestion commerciale.</p>
    </div>
</section>

<section class="experience">
    <h2>Expérience Professionnelle</h2>
    <div class="work-info">
        <h3>Vendeur chez Decathlon</h3>
        <p>Rôle : Vente en magasin, gestion des stocks et conseils clients.</p>
    </div>
    <div class="work-info">
        <h3>Stage chez Birdie</h3>
        <p>Rôle : Assistant dans le développement de produits innovants, gestion des tâches de projet et coordination avec les équipes.</p>
    </div>
    <div class="work-info">
        <h3>Stage en Jardinage</h3>
        <p>Rôle : Apprentissage des techniques de jardinage et gestion des espaces verts.</p>
    </div>
</section>

<section class="contact">
    <h2>Contact</h2>
    <p class="contact-info">Email : <a href="mailto:maxime.farfan@gmail.com">maxime.farfan@gmail.com</a></p>
    <p class="contact-info">Téléphone : <a href="tel:+33750446130">07 50 44 61 30</a></p>
</section>

<footer>
    <p>Portfolio réalisé par Maxime Farfan Escobar &copy; 2024</p>
</footer>

</body>
</html>
