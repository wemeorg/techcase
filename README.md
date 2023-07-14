<p align="center">
  <a href="https://www.weme.com.br/">
    <img src="https://uploads-ssl.webflow.com/64777a8d9e690fab7ae929ff/649bd8ed4b3a895b4e593264_Group%2083.svg" alt="weme logo" width="200" height="78"/>
  </a>
</p>

## weme - Case FullStack

Sabemos o quão difícil pode ser lembrar de todas as senhas que usamos diariamente - redes sociais, serviços, cartões... e a lista só cresce! Sendo assim, _**seu desafio é criar uma aplicação que permita ao usuário armazenar, visualizar e gerenciar todas essas credenciais em um só lugar.**_

## Instruções Backend

*   Desenvolva uma API REST;
*   Utilize TypeScript com Node.js;
*   O Banco de dados pode ser Postgres ou MySQL;
*   Recomendamos a utilização de ExpressJS (ou NestJS, se já tiver conhecimento!);
*   Utilize um ORM (recomendamos TypeORM) para o gerenciamento do banco de dados;
*   No entanto, sinta-se à vontade para escolher bibliotecas, arquitetura, etc.;
*   Escreva um README com todas as instruções para executarmos a sua aplicação.

## Instruções Frontend

*   Desenvolva uma SPA (Single Page Application);
*   Utilize React ou Nextjs;
*   Fique à vontade para utilizar bibliotecas, frameworks, etc. (inclusive de estilização);
*   Escreva um README com as instruções para executarmos a sua aplicação.

## Requisitos obrigatórios

#### 1\. Sistema de autenticação:

*   **Cadastro:** o usuário deve fornecer um nome, um e-mail válido e uma senha para criar uma conta. Se o e-mail já estiver em uso, a aplicação não deve permitir a criação da conta.
*   **Login:** o usuário deverá utilizar o e-mail e a senha cadastrados. Caso ele forneça dados incompatíveis, a aplicação deve informá-lo.  
    O usuário deve estar autenticado para a realização das atividades citadas no contexto.

#### 2\. Credenciais:

*   **Listagem das credenciais:** as credenciais do usuário devem ser listadas, podendo ser filtradas por tipo e ordenadas por data.
*   **Cadastro de credencial do tipo Cartão:** para registrar uma credencial do tipo cartão, o usuário deverá fornecer o número do cartão, o nome impresso, o código de segurança, a data de expiração, a senha e um título/nome/rótulo único.  
*   **Cadastro de credencial do tipo Email:** para registrar uma credencial do tipo Email, o usuário deverá fornecer uma URL referente ao cadastro que está sendo feito (ex.: https://mail.google.com/, https://outlook.live.com/), o e-mail, a senha e um título/nome/rótulo único.
*   **Edição das credenciais:** todas as credenciais do usuário devem poder ser editadas.
*   **Validação de Senhas Fortes:** deve sempre ser indicado a cada digitação, próximo ao campo da senha, a quantidade mínima de caracteres faltantes para ter uma senha forte! ([de acordo com o desafio de senhas fortes](https://github.com/wemeorg/techcase/blob/dev/strongpass.md)) <- clica aqui ;)

### Requisitos opcionais

*   Torne a aplicação responsiva.
*   Dockerize a aplicação (Frontend + Backend + Banco).
*   Documente o backend com Insomnia, Postman ou Swagger.
*   Faça o deploy da aplicação (Frontend + Backend + Banco).

### Durante o desenvolvimento, lembre-se:

*   Em caso de deploy, mantenha o banco de dados vazio e não teste com dados reais.
*   Em caso de duvida estaremos a disposição :)
*   Em caso de qualquer imprevisto, nos procure :)

### "we" more than "me". Vem conosco impulsionar um futuro melhor e sustentável para todos?
