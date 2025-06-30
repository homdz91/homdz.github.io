HOM_Site/
├── index.html
├── style.css
└── images/
    └── logo.png (à ajouter si tu veux le logo dans le site)


<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>House of Mona Algérie</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <img src="images/logo.png" alt="Logo HOM" class="logo" />
    <nav>
      <ul>
        <li><a href="#">Vêtements</a></li>
        <li><a href="#">Maquillage</a></li>
        <li><a href="#">Parfum</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>House of Mona</h1>
    <p>Élégance algérienne – Vêtements, maquillage et parfums</p>
    <a href="#" class="cta">Découvrir la collection</a>
  </section>

  <footer>
    <p>&copy; 2025 House of Mona – Algérie</p>
  </footer>
</body>
</html>

body {
  margin: 0;
  font-family: 'Playfair Display', serif;
  background-color: #f7f3ed;
  color: #222;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #fff;
}

.logo {
  height: 60px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 25px;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 80px 20px;
  background: linear-gradient(to bottom, #f5f0ea, #fff);
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 30px;
}

.cta {
  background-color: #000;
  color: #fff;
  padding: 12px 24px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #eae7e0;
  font-size: 14px;
}0
