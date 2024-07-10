# NLW JOURNEY - NODEJS - TRILHA BACK-END

### Criar o arquivo package.json
1 - npm init -y

### Utilizar Typescript
 2 - npm i typescript @types/node -D

### Criar arquivo de configuração do typescript
 3 - npx tsc --init
 4 - Entrar na pagina do git tsconfig/base e copiar
 o codigo da versao do node que está sendo utilizada.

 ### Converter typescript para javascript
 5 - npm i tsx -D
 6 - npx tsx watch src/server.ts - rodar o arquivo
 7 - no pkage.json adicionar o "scripts": 
    "dev": "npx tsx watch src/server.ts" e depois usar npm run dev para rodar o arquivo