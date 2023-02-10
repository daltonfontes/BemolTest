<p align="center">
  <img src="https://s3-sa-east-1.amazonaws.com/prod-jobsite-files.kenoby.com/uploads/novabd-1598984273-bedigital-1584103456-iconepngpng.png" width="320"/>
</p>

# Descrição do desafio

Desenvolver um Omnichannel.

# Features

- [x] Cadastro de Usuario
- [x] Pagina de Login
- [x] Chat

# Tecnologias

- Laravel
- Sqlite
- Pusher

 ### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

[Git](https://git-scm.com), [Node](https://nodejs.org/en/). 

Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone https://github.com/daltonfontes/BemolTest


# Vá para a pasta server
$ cd BemolTest

# Instale as dependências
$ npm install

# Edite os campos abaixo no seu arquivo .env para configurar a base de dados.

DB_CONNECTION=sqlite

# Edite os campos abaixo no seu arquivo .env para configurar o broadcast.

BROADCAST_DRIVER=pusher

# Criar migrations
$ php artisan migrate


# Iniciar aplicação
$ php artisan serve
# O servidor inciará na porta:8000 - acesse <http://localhost:8000>
