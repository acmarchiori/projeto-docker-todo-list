# Aplicativo de Lista de Afazeres (ToDo App) 📋

Este repositório contém arquivos e códigos relacionados ao projeto de Lista de Afazeres, desenvolvido pela Trybe.

## Minha Contribuição 💡

Neste projeto, fui responsável por criar a estrutura do aplicativo de Lista de Afazeres (ToDo App). Isso incluiu a configuração do ambiente Docker utilizando o Docker Compose, o que facilitou a criação de um ambiente de desenvolvimento isolado e pronto para uso. Também configurei o docker-compose.yml, o Dockerfile e outros elementos essenciais.

## Créditos
Os arquivos e códigos das pastas `docker/todo-app` foram feitos pela [Trybe](https://www.betrybe.com/).

## Instruções de Uso 🚀

1. Certifique-se de ter o Docker instalado: [Documentação do Docker](https://docs.docker.com/get-docker/).
2. Clone este repositório: `git clone https://github.com/seudominio/todo-app.git`.
3. Navegue até a pasta clonada: `cd todo-app`.
4. Construa as imagens dos containers do frontend, backend e testes: `docker-compose build`.
5. Execute o comando Docker Compose: `docker-compose up`.
6. Abra seu navegador e acesse: `http://localhost:3000`.

## Comandos Úteis

- Para criar e iniciar os containers: `docker-compose up -d`
- Para parar os containers: `docker-compose down`
- Para verificar o status dos containers: `docker-compose ps`
- Para acessar o terminal de um container específico (por exemplo, backend): `docker-compose exec backend sh`

## Referências Úteis 🔍

- Documentação do Docker: [https://docs.docker.com](https://docs.docker.com)
- Tutorial de Docker Compose: [https://docs.docker.com/compose/](https://docs.docker.com/compose/)
- Páginas de Ajuda da Trybe: [https://www.betrybe.com/ajuda](https://www.betrybe.com/ajuda)

## Atenção

Este projeto foi desenvolvido como parte do currículo da Trybe e tem apenas propósitos educacionais.

