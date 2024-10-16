<h1 align="center" style="font-weight: bold;">Project name 💻</h1>

<p align="center">
    <b>Aqui vamos falar um pouco do nosso projeto, como ele funciona e como é possível usá-lo</b>
</p>

<h2 id="technologies">💻 Tecnologias</h2>

- liste aqui as tecnologias que usou
- Java
- MySQL
- Spring boot

<h2 id="started">🚀 Iniciando o projeto</h2>

Nessa parte auxiliamos as pessoas a rodar nosso projeto localmente

<h3>Pré Requisitos</h3>

Liste todos os pré requisitos para rodar seu projeto

- [Java](https://github.com/)
- [MySQL](https://github.com/)

<h3>Clonando</h3>

Como fazer o clone do projeto

```bash
git clone your-project-url-in-github
```

<h3>Iniciando</h3>

Como rodar o projeto

Construindo o Projeto:

```bash
.mvnw clean package

```

-Executando Projeto:

```bash
java -jar ./target/email-springboot-0.0.1-SNAPSHOT.jar

```

<h2 id="routes">📍 API Endpoints</h2>

Here you can list the main routes of your API, and what are their expected request bodies.
​

<h3 id="get-auth-detail">GET /product</h3>

**RESPONSE**

```json
{
  "id": 1,
  "name": "Orange Juice",
  "category": "beverage",
  "price": 9.99
}
```

<h3 id="post-auth-detail">POST /product</h3>

**REQUEST**

```json
{
  {
  "name": "Orange Juice",
  "category": "beverage",
  "price": 9.99
}
}
```

**RESPONSE**

```json
{
  "message": "The product has been added successfully."
}
```
