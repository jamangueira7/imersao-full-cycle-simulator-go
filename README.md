<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-rodar">Como rodar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como contribuir</a>&nbsp;&nbsp;&nbsp;
  </p>

<br>

## Full Cycle - Simulador Go

<p align="center">
  <img alt="producer" src=".github/img.png">
</p>

<p align="center">
  <img alt="app" src=".github/img_1.png">
</p>

<p align="center">
  <img alt="consumer" src=".github/img_2.png">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Docker](https://www.docker.com/)
- [Kafka](https://kafka.apache.org/)
- [Go](https://go.dev/)

## 💻 Projeto

Simulador para gerar posições no map (latitude e longitude).

[nest-api](https://github.com/jamangueira7/imersao-full-cycle-api-nestjs)
[apache-kafka](https://github.com/jamangueira7/imersao-full-cycle-apache-kafka)

[frontend](https://github.com/jamangueira7/imersao-full-cycle-react-ts)

## 🚀 Como Rodar

- Clone o projeto.
- Entre na pasta do projeto e crie um arquivo .env na raiz do projeto com os valores que estão em .env.example
-  Rode `docker-compose up -d`.
- Entre no container com o comando `docker exec -it simulator bash`. Quando entrar execute o comando `go run main.go`. Esse terminal estará escutando as mensagens.

## 🤔 Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

## 📝 Licença

Esse projeto está sob a licença MIT.
