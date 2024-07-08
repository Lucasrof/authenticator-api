Authenticator API
Este projeto consiste em uma API para autenticação utilizando Java 17. A API permite o registro de usuários, login seguro e autenticação de requisições.

Funcionalidades
Registro de Usuário: Permite que novos usuários se cadastrem fornecendo um nome de usuário e senha. A senha é armazenada de forma segura após ser criptografada.

Login: Permite que usuários registrados façam login utilizando seu nome de usuário e senha. A autenticação é feita de forma segura.

Requisições Autenticadas: Determinadas partes da aplicação requerem que o usuário esteja autenticado para acessá-las. Isso é feito através de tokens de autenticação que são gerados durante o processo de login e usados para verificar a identidade do usuário em cada requisição subsequente.

Tecnologias Utilizadas
Java 17: Linguagem de programação utilizada para desenvolver a API.

Spring Boot: Framework utilizado para facilitar a configuração da API em Java.

Angular 18: Framework de front-end utilizado para construir a interface de usuário interativa.

JWT (JSON Web Tokens): Utilizado para gerenciar tokens de autenticação.

Banco de Dados: A titulo de projeto inicialmente utilizei o BD local, porém, será implementado futuramente um BD relacional. 

Segurança: As boas práticas de segurança são seguidas para proteger as informações dos usuários, incluindo armazenamento seguro de senhas e comunicação criptografada.

Como Usar
Para utilizar este projeto localmente, siga os passos abaixo:

Clone o Repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
Configuração da API:

Configure o banco de dados conforme especificado no arquivo application.properties ou similar.
Execute a API Spring Boot utilizando a IDE de sua preferência ou via linha de comando.
Configuração do Front-end:

Navegue até o diretório frontend e instale as dependências do Angular:
bash
Copiar código
cd frontend
npm install
Inicie o Servidor de Desenvolvimento do Angular:

css
Copiar código
ng serve --port 4200
Acesse a Aplicação no Navegador:
Abra seu navegador e acesse http://localhost:4200.

