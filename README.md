# nodejs-rs-module-02
Modulo dois do Bootcamp


Todos os npm usados neste projeto

# Criar projeto:
npm init -y

# Dependencias de Desenvolvimento
npm install -D nodemon
npm install -D nodemon@1.0.6


# Dependencias
npm install express // Similar o http
npm install body-parser // Obrigatório instalar junto com o express, converte e facilita o entendimento das requesições FORM
npm install nunjucks // Similar ao Twig, forma de visualização. DETALHE! Falta configura existente no site da nunjucks
npm install mongoose // Banco de dados SEM TABELAS!!!
npm install bcryptjs // Usado para gerar senhas cryptografadas
npm install connect-flash // Callback pra notificações
npm install express-session // Pra armazenar sessões do usuário
npm install connect-session-sequelize // Recupera dados da sessões dos usuários


npm install sequelize // Banco de dados [Similar ao Hibernate ou Doctrine] Postgres e MySql 
// .\node_modules\.bin\sequelize init
// .\node_modules\.bin\sequelize db:create
// .\node_modules\.bin\sequelize migration:create --name=create-users  // Comando pra criar o migration
// .\node_modules\.bin\sequelize db:migrate // Manda dados da pasta migrate para o banco
npm install -D sequelize-cli // Dependencia do sequelize

# Dependencias extras
npm install momentjs // Manipular datas
npm install markdown-it
npm install highlight.js
npm install method-override // Auxilia e troca o tipo da requisição do Form -> Usado com o Express
