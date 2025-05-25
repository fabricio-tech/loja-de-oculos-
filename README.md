<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Loja de Óculos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav {
      background-color: #555;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    main {
      padding: 20px;
      text-align: center;
    }
    .produto {
      border: 1px solid #ccc;
      padding: 15px;
      margin: 15px;
      display: inline-block;
      width: 200px;
    }
    .produto img {
      width: 100%;
      height: auto;
    }
    footer {
      background-color: #333;
      color: white;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>Visão Estilo - Loja de Óculos</h1>
  </header>

  <nav>
    <a href="#">Início</a>
    <a href="#">Produtos</a>
    <a href="#">Contato</a>
    <a href="#">Sobre</a>
  </nav>

  <main>
    <h2>Nossos Produtos</h2>

    <div class="produto">
      <img src="https://via.placeholder.com/200x120.png?text=Óculos+1" alt="Óculos 1">
      <h3>Óculos Clássico</h3>
      <p>R$ 199,90</p>
      <button>Comprar</button>
    </div>

    <div class="produto">
      <img src="https://via.placeholder.com/200x120.png?text=Óculos+2" alt="Óculos 2">
      <h3>Óculos Moderno</h3>
      <p>R$ 249,90</p>
      <button>Comprar</button>
    </div>

    <div class="produto">
      <img src="https://via.placeholder.com/200x120.png?text=Óculos+3" alt="Óculos 3">
      <h3>Óculos de Sol</h3>
      <p>R$ 179,90</p>
      <button>Comprar</button>
    </div>
  </main>

  <footer>
    <p>Desenvolvido por Seu Nome - © 2025</p>
  </footer>
</body>
</html>
