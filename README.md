# cadastro-produtos
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Cadastro de Produtores </title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <header class="bg-dark text-white text-center py-3 mb-4">
    <h1>Cadastro de Produtores Culturais</h1>
  </header>

  <main class="container">
    <form class="row g-3">
      <div class="col-md-12">
        <label for="nome" class="form-label">Nome</label>
        <input type="text" class="form-control" id="nome" placeholder="Digite o nome completo">
      </div>
      <div class="col-md-6">
        <label for="endereco" class="form-label">Endereço</label>
        <input type="text" class="form-control" id="endereco" placeholder="Rua, Avenida...">
      </div>
      <div class="col-md-3">
        <label for="numero" class="form-label">Número</label>
        <input type="text" class="form-control" id="numero" placeholder="Ex: 123">
      </div>
      <div class="col-md-3">
        <label for="complemento" class="form-label">Complemento</label>
        <input type="text" class="form-control" id="complemento" placeholder="Apto, Bloco...">
      </div>
      <div class="col-md-8">
        <label for="email" class="form-label">E-mail</label>
        <input type="email" class="form-control" id="email" placeholder="exemplo@email.com">
      </div>
      <div class="col-md-4">
        <label for="telefone" class="form-label">Telefone</label>
        <input type="tel" class="form-control" id="telefone" placeholder="(xx) xxxxx-xxxx">
      </div>
      <div class="col-12 text-center">
        <button type="submit" class="btn btn-primary">Enviar Cadastro</button>
      </div>
    </form>
  </main>
  <footer class="bg-light text-center py-3 mt-4 border-top">
    <p class="mb-0">© 2025 - Cadastro de Produtores Culturais</p>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
