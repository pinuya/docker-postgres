# Como Rodar o Docker-Compose com PostgreSQL e Adminer

Este projeto utiliza o Docker Compose para configurar um banco de dados PostgreSQL junto com o Adminer, uma ferramenta de gerenciamento de banco de dados web. Abaixo estão as instruções para iniciar esses serviços.

## Pré-requisitos

Antes de começar, certifique-se de que você tenha os seguintes softwares instalados:

- Docker (versão 1.26.0 ou superior)
- Docker Compose (versão 1.21.0 ou superior)

## Instruções para Execução

1. Inicie os Serviços:
   Execute o seguinte comando para iniciar os serviços:
   `docker-compose up`
   Isso irá baixar as imagens do PostgreSQL e do Adminer, criar os containers e iniciar os serviços.

2. Acesse o Adminer
   Após os serviços estarem em execução, abra seu navegador e acesse:
   `http://localhost:8080`
   Você verá a interface do Adminer.

## Configurações do Adminer

Ao acessar o Adminer, utilize as seguintes credenciais para se conectar ao banco de dados PostgreSQL:

- Sistema de banco de dados: PostgreSQL
- Servidor: db
- Nome de usuário: postgres
- Senha: example
- Banco de dados: (deixe em branco para conectar ao banco padrão)
