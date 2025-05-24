# DAN-S7
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Mods Pronto Bus Simulator</title>
<style>
  /* Reset básico */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #f9f9f9;
    color: #333;
    line-height: 1.6;
  }
  header {
    background-color: #004d99;
    color: white;
    padding: 20px 0;
    text-align: center;
  }
  header h1 {
    font-weight: 700;
    font-size: 2rem;
    letter-spacing: 2px;
  }
  nav {
    margin-top: 10px;
  }
  nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: 600;
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #ffcc00;
  }
  main {
    max-width: 900px;
    margin: 30px auto;
    padding: 0 20px;
  }
  section {
    margin-bottom: 40px;
    background: white;
    border-radius: 8px;
    padding: 25px 30px;
    box-shadow: 0 4px 10px rgb(0 0 0 / 0.1);
  }
  section h2 {
    color: #004d99;
    margin-bottom: 20px;
    border-bottom: 3px solid #004d99;
    padding-bottom: 6px;
  }
  ul {
    list-style: disc inside;
  }
  ul li {
    margin-bottom: 12px;
  }
  .mod-item {
    margin-bottom: 18px;
  }
  .mod-item strong {
    color: #004d99;
  }
  .btn-link {
    display: inline-block;
    background-color: #004d99;
    color: white;
    text-decoration: none;
    padding: 10px 16px;
    border-radius: 5px;
    font-weight: 600;
    transition: background-color 0.3s ease;
  }
  .btn-link:hover {
    background-color: #003366;
  }
  footer {
    background: #222;
    color: #ddd;
    text-align: center;
    padding: 18px 0;
    font-size: 0.9rem;
  }
  @media (max-width: 600px) {
    nav a {
      display: block;
      margin: 10px 0;
    }
    main {
      padding: 0 15px;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Mods Pronto Bus Simulator</h1>
  <nav>
    <a href="#onibus">Ônibus</a>
    <a href="#mapas">Mapas</a>
    <a href="#skins">Skins</a>
    <a href="#instalar">Como Instalar</a>
    <a href="#apps">Apps</a>
  </nav>
</header>

<main>
  <section id="onibus">
    <h2>Ônibus Disponíveis</h2>
    <div class="mod-item">
      <strong>Mercedes-Benz Citaro O530</strong>
      <p>Ônibus urbano moderno, ideal para rotas movimentadas.</p>
    </div>
    <div class="
