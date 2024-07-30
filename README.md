# Projeto de Cadastro

Este projeto é uma página HTML simples para cadastro de informações pessoais. Utiliza o Bootstrap para estilização e proporciona um formulário com campos básicos.

## Estrutura do Projeto

O projeto contém um único arquivo HTML com o seguinte conteúdo:

- **`index.html`**: Página principal contendo um formulário de cadastro.

## Descrição do Formulário

O formulário inclui os seguintes campos:

- Nome completo
- Endereço
- Telefone
- Email
- Data de Nascimento

## Código HTML

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <!-- Meta tags Obrigatórias -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/bootstrap.min.css">

    <title>Cadastrar</title>
  </head>
  <body>
    <header></header>

    <main class="container">
        <h1>Cadastrar</h1>

        <form>
                <div class="form-group">
                    <label for="nome">Nome completo</label>
                    <input type="text" class="form-control" id="nome">
                </div>
                <div class="form-group">
                    <label for="endereco">Endereço </label>
                    <input type="text" class="form-control" id="endereco">
                </div>
                <div class="form-group">
                    <label for="telefone">Telefone</label>
                    <input type="text" class="form-control" id="telefone">
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" class="form-control" id="email1">
                </div>
                <div class="form-group">
                    <label for="data">Data de Nascimento</label>
                    <input type="date" class="form-control" id="date">
                </div>
                <button type="submit" class="btn btn-primary">Cadastrar</button>
        </form>
        </main>

    <footer></footer>

  </body>
</html>
