<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FlexBox</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background-color: #f0f0f0;
    }

    h1, h2 {
      text-align: center;
    }

    h1 {
      margin-top: 30px;
    }

    nav {
      display: flex;
      justify-content: space-around;
      align-items: center;
      background-color: black;
      padding: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 20px;
    }

    nav a:hover {
      color: yellow;
    }

    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
      background-color: white;
      margin: 30px;
      padding: 30px;
      border: 3px solid black;
      min-height: 300px;
    }

    .item {
      width: 120px;
      height: 120px;
      background: royalblue;
      color: white;
      font-size: 30px;
      display: flex;
      justify-content: center;
      align-items: center;
      border-radius: 10px;
      transition: 0.5s;
    }

    .item:hover {
      transform: scale(1.1);
      background: crimson;
    }

    .cards {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
      margin: 30px;
    }

    .card {
      width: 250px;
      height: 250px;
      background: white;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      transition: 0.5s;
      padding: 15px;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .descricao {
      text-align: center;
      max-width: 800px;
      margin: auto;
      padding: 10px 20px;
    }

    .beneficios {
      background-color: white;
      margin: 30px;
      padding: 20px;
      border-radius: 10px;
    }

    .beneficios ul {
      list-style: none;
      padding: 0;
      text-align: center;
    }

    .beneficios li {
      padding: 10px;
      font-size: 18px;
    }

    footer {
      background-color: black;
      color: white;
      text-align: center;
      padding: 30px;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#inicio">Home</a>
    <a href="#sobre">Sobre</a>
    <a href="#tecnologias">Tecnologias</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="inicio">
    <h1>🚀 Aprendendo FlexBox com HTML e CSS</h1>

    <p class="descricao">
      Este projeto demonstra a utilização do FlexBox para criar layouts modernos,
      organizados e responsivos, facilitando o desenvolvimento de páginas web.
    </p>
  </section>

  <section id="sobre">
    <h2>📚 Sobre o Projeto</h2>

    <p class="descricao">
      FlexBox é uma ferramenta poderosa do CSS que permite alinhar e distribuir
      elementos de forma simples, tornando os sites mais bonitos e adaptáveis
      a diferentes tamanhos de tela.
    </p>
  </section>

  <div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
    <div class="item">5</div>
    <div class="item">6</div>
    <div class="item">7</div>
    <div class="item">8</div>
  </div>

  <section id="tecnologias">
    <h2>🛠 Tecnologias Utilizadas</h2>

    <div class="cards">

      <div class="card">
        <div>
          <h3>💻 HTML</h3>
          <p>Responsável pela estrutura e organização do conteúdo da página.</p>
        </div>
      </div>

      <div class="card">
        <div>
          <h3>🎨 CSS</h3>
          <p>Utilizado para estilizar e deixar a página visualmente agradável.</p>
        </div>
      </div>

      <div class="card">
        <div>
          <h3>⚡ JavaScript</h3>
          <p>Permite adicionar interatividade e recursos dinâmicos.</p>
        </div>
      </div>

      <div class="card">
        <div>
          <h3>🚀 Projetos</h3>
          <p>Desenvolvimento de páginas modernas e responsivas.</p>
        </div>
      </div>

    </div>
  </section>

  <section class="beneficios">
    <h2>⭐ Benefícios do FlexBox</h2>

    <ul>
      <li>✔ Alinhamento simplificado dos elementos</li>
      <li>✔ Layout responsivo para diferentes dispositivos</li>
      <li>✔ Melhor organização visual</li>
      <li>✔ Menos código para posicionamento</li>
      <li>✔ Facilidade de manutenção</li>
      <li>✔ Compatibilidade com navegadores modernos</li>
    </ul>
  </section>

  <footer id="contato">
    <h3>🚀 SENAI JAÚ</h3>

    <p>
      Projeto desenvolvido para estudos de HTML, CSS e FlexBox.
    </p>

    <p>📧 contato@senai.com.br</p>

    <p>📱 (14) 99999-9999</p>

    <p>💻 Desenvolvimento Web Front-End</p>

    <p>© 2026 - Todos os direitos reservados.</p>
  </footer>

</body>
</html>
