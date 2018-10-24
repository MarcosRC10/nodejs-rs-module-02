# nodejs-rs-module-02
Modulo dois do Bootcamp


Todos os npm usados neste projeto

# Criar projeto:
npm init -y <br>

# Dependencias de Desenvolvimento
npm install -D nodemon <br>
npm install -D nodemon@1.0.6 <br>
# Dependencias
npm install express // Similar o http <br>
npm install body-parser // Obrigatório instalar junto com o express, converte e facilita o entendimento das requesições FORM<br>
npm install nunjucks // Similar ao Twig, forma de visualização. DETALHE! Falta configura existente no site da nunjucks<br>
npm install mongoose // Banco de dados SEM TABELAS!!!<br>
npm install bcryptjs // Usado para gerar senhas cryptografadas<br>
npm install connect-flash // Callback pra notificações<br>
npm install express-session // Pra armazenar sessões do usuário<br>
npm install connect-session-sequelize // Recupera dados da sessões dos usuários<br>

npm install sequelize // Banco de dados [Similar ao Hibernate ou Doctrine] Postgres e MySql <br>
// .\node_modules\.bin\sequelize init<br>
// .\node_modules\.bin\sequelize db:create<br>
// .\node_modules\.bin\sequelize migration:create --name=create-users  // Comando pra criar o migration<br>
// .\node_modules\.bin\sequelize db:migrate // Manda dados da pasta migrate para o banco<br>
npm install -D sequelize-cli // Dependencia do sequelize<br>

# Dependencias extras
npm install momentjs // Manipular datas<br>
npm install markdown-it<br>
npm install highlight.js<br>
npm install method-override // Auxilia e troca o tipo da requisição do Form -> Usado com o Express<br>
