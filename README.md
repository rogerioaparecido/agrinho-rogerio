# agrinho-rogerio
estrutura html 
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Conexão Campo & Cidade</title>
  <link rel="stylesheet" href="estilo.css">
</head>
<body>

  <header>
    <h1>Conexão Campo & Cidade</h1>
    <p>Um projeto que celebra a união entre dois mundos essenciais</p>
  </header>

  <section class="banner">
    <h2>Bem-vindo ao Projeto Agrinho</h2>
    <p>Aqui os alunos exploram como o campo e a cidade se complementam.</p>
  </section>

  <section class="sobre">
    <h2>Sobre o Projeto</h2>
    <p>O campo produz, a cidade transforma. Juntos, constroem o nosso dia a dia. Este espaço é dedicado à valorização de ambos os ambientes por meio de textos, imagens e criatividade dos alunos.</p>
  </section>

  <section class="galeria">
    <h2>Galeria de Imagens</h2>
    <div class="imagem-box">
      <p><strong>Campo:</strong></p>
      <img src="" alt="Imagem do campo" class="imagem-exemplo">

      <p><strong>Cidade:</strong></p>
      <img src="" alt="Imagem da cidade" class="imagem-exemplo">
    </div>
  </section>

  <section class="textos">
    <h2>Textos e Reflexões</h2>
    <p><strong>1. O que o campo representa para você?</strong></p>
    <textarea rows="4" placeholder="Escreva aqui..."></textarea>

    <p><strong>2. Como a cidade se conecta com a vida rural?</strong></p>
    <textarea rows="4" placeholder="Digite sua resposta..."></textarea>
  </section>

  <footer>
    <p>&copy; 2025 – Projeto Agrinho | Escola ____________________</p>
  </footer>

</body>
</html>


Estrutura css
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #d0f0c0; /* fundo verde claro */
  color: #333;
}

header {
  background-color: #388e3c;
  color: white;
  text-align: center;
  padding: 2rem 1rem;
}

header h1 {
  margin: 0;
}

.banner {
  background-color: #f1f8e9;
  text-align: center;
  padding: 2rem 1rem;
}

.sobre {
  background-color: #ffffff;
  padding: 2rem;
}

.galeria {
  background-color: #fce4ec;
  padding: 2rem;
}

.textos {
  background-color: #e3f2fd;
  padding: 2rem;
}

textarea {
  width: 100%;
  padding: 10px;
  margin-top: 0.5rem;
  margin-bottom: 1.5rem;
  border: 1px solid #ccc;
  border-radius: 6px;
  resize: vertical;
}

img.imagem-exemplo {
  width: 100%;
  max-width: 600px;
  height: auto;
  border: 3px dashed #4CAF50;
  border-radius: 10px;
  margin: 1rem 0;
}

footer {
  background-color: #2e7d32;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}