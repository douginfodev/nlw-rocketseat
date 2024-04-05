1 - npm init -y
2 - npm i typescript @types/node -D

# Atulizar o node
npm install -g npm@9.6.6

3 - npx tsc --init
4 - npm i tsx -D
5 - npm i  fastify -D
6 - npm install eslint -D

# Instalar o Prisma ORM
npx prisma init --datasource-provider SQLite

# rodar a migrate
1 - npx prisma migrate dev 
2 = Digitar nome da migrate <nome dado a 
migrate>
3 resetar a migratee npx prisma migrate reset

# Visualizar as tabelas e dados
npx prisma studio

# acessar o Banco
npm i @prisma/client