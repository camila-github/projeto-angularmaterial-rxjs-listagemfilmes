## Projeto: Criação de site com listagem de filmes com Angular Material + RxJS + Json-server

- O objetivo do projeto é criar um site que consta uma lista de filmes, que seja possivel cadastrar, excluir, consultar e editar os filmes utilizando como backend arquivo .json. Na parte do FrontEnd será utilizado o Angular Material + RxJS + SCSS e na parte do Backend será utilizado o json-server para simular um backend com requisições Rest.

## Ferramentas utilizadas:


##### NODEJS 

- Abaixo link para download:

	[https://nodejs.org/en/](https://nodejs.org/en/)


##### ANGULAR 8

- Link de referencia: 

	[https://cli.angular.io/](https://cli.angular.io/)

- Caso não tiver o angular instalado utilize o comando abaixo para instalar o angular: 

	`$ npm install -g @angular/cli`

- O comando abaixo verifica a versão do angular após instalação: 

	`$ ng version`

- Para criar novo projeto angular, execute o comando abaixo. Será criado a estrutura de pastas padrão do angular: 

	`$ ng new 'nome-do-projeto'`

- Para iniciar o servidor do angular, utilize o comando abaixo:

	`$ npm start`

	ou 

	`$ ng serve`

- O link abaixo é referente a rota que foi criada para acessar o 'index.html':

	[http://localhost:4200/](http://localhost:4200/)


##### ANGULAR MATERIAL 

- É uma biblioteca de componentes para o Angular. O Angular Material é a implementação oficial, para o Angular, do Material Design, a especificação de design para interfaces interativas do Google. O Material Design cobre desde pequenos elementos, como ícones e cores, até elementos maiores como navegação, cards, imagens, entre outros.

- Link da documentação:

	[https://material.angular.io/guide/getting-started](https://material.angular.io/guide/getting-started)

- Comando para instalar o Angular Material no projeto:

	`$ ng add @angular/material`

- Apos instalação é questionado:

	````
  Choose a prebuilt theme name, or "custom" for a custom theme: (Use arrow keys)

	(Eu escolhi o 'Indigo/Pink')

	Set up global Angular Material typography styles? (y/N)

	(Eu escolhi 'y')

	Set up browser animations for Angular Material? (Y/n)

	(Eu escolhi 'y')
  ````

##### JSON SERVER

- O JSON-Server é um pacote npm que pode ser usado para criar um webservice REST JSON simulando uma API. Nesse projeto o 'json-server' será o responsável por criar o back-end, ou seja, o 'json-server' irá criar os arquivos mockeados dentro de um arquivo chamado db.json, com isso será possivel fazer chamadas REST (post, get, delete, put ) nesse arquivo, é como se estivesse acessando um banco de dados, mas nesse caso, será acessado um arquivo em json.

- Abaixo o comando para instalar o json-server: 

	`$ npm install -g json-server`

- O comando abaixo é para iniciar o 'json-server'. Detalhe: Se não existir o arquivo 'db.json' o proprio 'json-server' irá criar:

	`$ json-server --watch db.json`

- Assim que o servidor 'json-server' for iniciado, è possivel acessar o conteudo do arquivo 'db.json', na rota abaixo:

	[http://localhost:3000/filmes](http://localhost:3000/filmes)


##### POSTMAN

- Para fins de testes, para fazer requisições Rest(get, post, put, delete) e para verificar se esta funcionando o arquivo 'db.json', utilize o postman. No postman, utilize a rota que foi criada:

	[http://localhost:3000/filmes](http://localhost:3000/filmes)

 
##### NGX-Infinite-Scroll

- O NGX-Infinite-Scroll faz o Scroll infinito da tela, ou seja, o componente carrega o conteudo da pagina, conforme for rolando a tela.


##### RXJS

- O RxJS é uma biblioteca para programação reativa usando Observables, para facilitar a composição de codigo assíncrono ou baseado em retorno de chamada.

- O RxJS ja vem com o angular, nao precisa instalar.

- Link documentaçao:

	[https://rxjs-dev.firebaseapp.com/guide/overview](https://rxjs-dev.firebaseapp.com/guide/overview)

	[https://www.learnrxjs.io/](https://www.learnrxjs.io/)


##### CLONAR PROJETO NO GIT

- Ou se preferir, clone o projeto do github. Use o comando abaixo para baixar as pendencias, de acordo com o que esta no package.json. Nesse caso nao é necessario fazer toda a instalação das ferramentas citadas nos topicos acima.

- Primeiro copie o link no github. Acesse a pasta onde o projeto será salvo, e execute o comando abaixo, no terminal.

	`$ clone 'link do projeto no github'`

- Depois do download do projeto, execute o comando abaixo para instalar as pedencias de acordo com o que esta no package.json.

	`$ npm install`

- Para que o projeto funcione, necessario ter o 'json-server' iniciado com o comando abaixo:

	`$ json-server --watch db.json`

- E tambem, o 'server' do angular tem que estar iniciado, com um dos comandos abaixo:
	`$ npm start`

	ou 

	`$ ng serve`


## CONCEITO UTILIZADOS:

- Aplicação de FormBuilder do angular
- ValidaÇÃo dos campos do formulario
- Aplicação de Elvis Operator (Operação segura)
- Criação de serviço para validação de erros
- Componentização dos Inputs
- Aplicação de mensagens de erros dinâmicas
- Passando array com valores para o componente
- Criação de serviços e tratamento de retorno da modal
- Aplicação de Scroll Infinito (NGX-Infinite-Scroll)
- Aplicação de filtro e ordenação no formulario
- Utilização de HTTP Params
- Uso do NG-Template
- Aplicação de melhoria de performance
- Aplicação de estilos scss
- Aplicação de CRUD - Cadastrar - Listar - Editar - Excluir - (Sem banco de dados, será utilizado mocks de arquivos .json)
- Geração do Build - Para geração do build, execute `$ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicione `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.
- Link referencia: O projeto publicado é referente ao treinamento do Curso Bootcamp - Angular Developer da Digital Innovation One: [https://digitalinnovation.one](https://digitalinnovation.one)

