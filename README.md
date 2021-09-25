# Página de notícias utilizando PWA ReactJS

## Projeto desenvolvido durante Bootcamps da Digital Innovation One tendo como instrutor [Bruno Carneiro](linkedin.com/in/carneirobruno/).

O projeto tem por objetivo demonstrar o funcionamento dos conceitos de Progressive Web Application (PWA) e foi desenvolvida em ReactJS. \
O projeto busca simular uma página de notícias.

Para criar esse projeto usaremos React Js
Também é necessário ter instalado no computador o Node.js (https://nodejs.org/pt-br/) e o Gerenciador de Pacotes NPM, que já será instalado junto com o Node.js

Para desenvolver o projeto utilizamos o Visual Studio Code (VS Code).

Para criar o projeto crie em seu computador uma pasta com o nome que desejar, por exemplo: projeto-react

Abra a pasta no VS Code.

Dividimos o projeto em 2 partes:
 A parte do front-end da aplicação que irá rodar no navegador e uma parte com uma api que irá carregar as informações para o navegador.

Para criar o projeto digite o comando: `npx create-react-app <nome-do-projeto>`
Como exemplo eu utilizei: `npx create-react-app pwa-news-dio`

Aguarde um tempinho que o VS Code irá criar a estrutura do projeto.

Após finalizada a criação da estrutura das pastas do projeto, ainda no terminal integrado navegue para a pasta que foi criada utilize o comando: `cd pwa-news-dio`

Após se certificar que está na pasta correta você precisa instalar algumas bibliotecas:

[Ant Design](https://www.npmjs.com/package/antd) - comando de instalação: `npm install antd` \
[React-Router-DOM](https://www.npmjs.com/package/react-router-dom) - comando de instalação: `npm install --save react-router-dom`

Para inicializar o projeto confirme que está na pasta do projeto (pwa-news-dio) digite no terminal integrado do VS Code o comando `npm start`

A aplicação irá rodar no modo de desenvolvimento: \
Caso não abra de forma automática no seu navegador padrão, clique ou copie o seguinte link [http://localhost:3000](http://localhost:3000).

Para parar a aplicação pressione as Teclas CTRL + C no terminal integrado do VS Code.

Para configurar a parte da API clique na área do Explorador no VS Code e crie uma nova pasta na raiz do projeto.
No meu projeto eu criei a pasta com o nome pwa-news-api \
Após criar a pasta vá ao terminal integrado do VS Code  e adicione um novo terminal para utilizar a API e o Front ao mesmo tempo, em seguida no terminal aberto para \
usar com a API navegue para a pasta criada utilizando o comando `cd pwa-news-api` .\

Após confirmar que está na pasta da API digite o comando: `npm init` para criar o arquivo package.json da API.\

Em seguida instale as seguintes bibliotecas: \
[express](https://www.npmjs.com/package/express) - comando de instalação: `npm install express` \
[cors](https://www.npmjs.com/package/cors) - comando de instalação: `npm install cors` \
[nodemon](https://www.npmjs.com/package/nodemon) - comando de instalação: `npm install --save-dev nodemon` 

No arquivo package-json da API faça a seguinte inserção: \
Em scripts adicione: `"dev": "nodemon --experimental-json-modules index.mjs",`

Para rodar a aplicação API digite o comando `npm run dev`

Para voltar a rodar a aplicação Front pwa-news digite no terminal integrado do VS Code o comando `npm start`, provavelmente irá aparecer uma mensagem informando que já está \
sendo utilizada a porta 3000 e vai perguntar se deseja utilizar outra porta, apenas digite `y` para confirmar e a aplicação voltará a rodar no navegador.

Copie o arquivo .gitignore da pasta pwa-news e cole na pasta pwa-new-api. \
Desta forma ao subir o projeto para o Github as dependências serão ignoradas.


Caso você prefira fazer o download desse repositório ou realizar o clone do repositório não de esqueça de instalar as dependências do Node JS. para isso assim que abrir o projeto no seu VS Code digite o comando npm install e depois não se esqueça de instalar as outras bibliotecas utilizadas no projeto conforme orientações acima.
