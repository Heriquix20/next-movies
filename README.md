
  <img src="images/logo_transparent.png" width="200" height="200" style="vertical-align: middle; display: block; margin-left: auto; margin-right: auto;">

## Next Movies

[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

**Next Movies é uma aplicação backend desenvolvida em Java com Spring Boot que consome 
a API do TMDb (The Movie Database) para buscar informações sobre filmes. 
A aplicação permite que os usuários pesquisem filmes, salvem os resultados das 
pesquisas no banco de dados, criem contas, façam login com autenticação via tokens,
favoritem filmes, removam favoritos e selecionem um filme aleatório da lista de 
favoritos para assistir.** <br>
<br>

![Inicio](images/inicio.jpg)

## Funcionalidades 📝

- **Busca de Filmes**: Utiliza a API do TMDb para pesquisar e exibir informações sobre filmes.
- **Autenticação de Usuário**: Sistema de criação de conta e login com tokens JWT para autenticação.
- **Criptografia de Senhas**: Senhas dos usuários são criptografadas antes de serem armazenadas no banco de dados.
- **Gerenciamento de Favoritos**: Usuários podem favoritar e remover filmes da lista de favoritos.
- **Seleção de Filme Aleatório**: Funcionalidade para selecionar um filme aleatório da lista de favoritos para assistir.
- **Tratamento de Erros HTTP**: Tratamento adequado de erros HTTP com respostas informativas para o cliente.


## Tecnologias Utilizadas 🖥️
[![Spring](https://img.shields.io/badge/Spring-6DB33F.svg?style=for-the-badge&logo=Spring&logoColor=white)](https://spring.io/)
[![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F.svg?style=for-the-badge&logo=Spring-Security&logoColor=white)](https://spring.io/projects/spring-security)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white)](https://www.mysql.com/)
[![JSON Web Tokens](https://img.shields.io/badge/JSON%20Web%20Tokens-000000.svg?style=for-the-badge&logo=JSON-Web-Tokens&logoColor=white)](https://jwt.io/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.java.net/)

- **Linguagem de Programação**: Java
- **Framework**: Spring Boot
- **Banco de Dados**: MySQL
- **Autenticação**: JWT (JSON Web Tokens)
- **API de Filmes**: TMDb (The Movie Database)



### API Endpoints

```bash
- **GET /filmes - Retorna a lista completa dos filmes.
- **GET /gen/{genero} - Retorna filmes filtrados pelo gênero.
- **GET /ordem/alfabetica** - Retorna filmes em ordem alfabética.
- **GET /ordenar/avaliacao** - Retorna filmes ordenados por avaliação.
- **GET /{titulo} - Retorna filmes correspondentes ao título pesquisado.
- **POST /login - Valida login e retorna o token de acesso.
- **POST /usuarios - Cadastra um novo usuário.
```


## Criação do Token JWT 🔑

Abaixo está um exemplo de como é feita a criação do token JWT no nosso projeto:

![Criação do Token JWT](images/jwt_creation.png)

Neste exemplo, mostramos a geração do token JWT com base nas credenciais do usuário e o retorno para o cliente.


## Controle de Acesso 🔒

Abaixo está um exemplo de como é o controle de acesso na nossa aplicação:

![Controle de Acesso](images/controle_de_acesso.png)


## Como Contribuir 🚀

Se você gostaria de contribuir para este projeto, siga os passos abaixo:

1. **Fork** o projeto.
2. Crie uma nova branch com sua feature:
```bash
git checkout -b minha-feature
```
Commit suas mudanças:
```bash
git commit -m 'Adiciona minha feature'
```
Push para a branch:
```bash
git push origin minha-feature
```
Envie um Pull Request explicando suas alterações. <br><br>
**Agradecemos sua contribuição!** 🎉


## Desenvolvimento 👩‍💻👨‍💻

- **Henrique**: Desenvolvimento BackEnd e Banco de Dados 🛠️ <br>
  - [Linkedin](http://www.linkedin.com/in/henrique-cezar)
  - Email: [hcgv1@hotmail.com](mailto:hcgv1@hotmail.com)
- **Isadora**: Desenvolvimento FrontEnd 💻 <br>
  - [Linkedin](https://www.linkedin.com/in/isadora-rodrigues-904b36164/)
  - Email: [isadoradorarodrigues@gmail.com](mailto:isadoradorarodrigues@gmail.com)


**Link do repositório front-end:** https://github.com/isadoritas/projeto-A03-2024-front

![Sobre nós](images/nosso_time.jpg)

 
