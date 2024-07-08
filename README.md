<h2>Authenticator API</h2>
Este projeto consiste em uma API para autenticação utilizando Java 17. A API permite o registro de usuários, login seguro e autenticação de requisições.

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:

- [Java 17](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
- [Node.js](https://nodejs.org/)
- [Maven](https://maven.apache.org/)


<h2>Funcionalidades</h2>
Registro de Usuário: Permite que novos usuários se cadastrem fornecendo um nome de usuário e senha. A senha é armazenada de forma segura após ser criptografada.

Login: Permite que usuários registrados façam login utilizando seu nome de usuário e senha. A autenticação é feita de forma segura.

Requisições Autenticadas: Determinadas partes da aplicação requerem que o usuário esteja autenticado para acessá-las. Isso é feito através de tokens de autenticação que são gerados durante o processo de login e usados para verificar a identidade do usuário em cada requisição subsequente.

<h2>Tecnologias Utilizadas</h2>
Java 17: Linguagem de programação utilizada para desenvolver a API.

Spring Boot: Framework utilizado para facilitar a configuração da API em Java.

Angular 18: Framework de front-end utilizado para construir a interface de usuário interativa.

JWT (JSON Web Tokens): Utilizado para gerenciar tokens de autenticação.

Banco de Dados: A titulo de projeto inicialmente utilizei o BD local, porém, será implementado futuramente um BD relacional. 

Segurança: As boas práticas de segurança são seguidas para proteger as informações dos usuários, incluindo armazenamento seguro de senhas e comunicação criptografada.

<h2>Como Usar</h2>
Para utilizar este projeto localmente, siga os passos abaixo:

<b>Clone o Repositório:</b>

bash
Copiar código
git clone https://github.com/Lucasrof/authenticator-api.git

cd authenticator-api
<h2>Configuração da API:</h2>

Configure o banco de dados conforme especificado no arquivo application.properties ou similar.
Execute a API Spring Boot utilizando a IDE de sua preferência ou via linha de comando.

<h2>Se optar pela integração com Front-end</h2>

Clone o repositório contido no link: https://github.com/Lucasrof/first-frontend-angular.git

Siga o passo a passo do Readme.



