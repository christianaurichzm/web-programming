# app-lembretes

Aplicação do tipo SPA (Single Page Application) que implementa autenticação de usuário utilizando o conceito de Java Web Token (JWT). Também acessa uma base de dados MongoDB para armazenar os dados dos usuários e seus respectivos lembretes.

Tokens no formato JWT (JSON Web Token).

## Instruções

Criar uma base de dados MongoDB, pode ser utilizando o mLab.

No diretório servidor criar um arquivo com nome .env contendo:

```
PORTA=3000
BD_URL=mongodb://....mlab.com:...
SENHA_JWT='senha super secreta'
DURACAO_JWT='1h'
SALT='Uma_frase_1mig1'
```

O valor da variável BD_URL deve ser a URL de acesso a base de dados.

1. `npm install`

2. `npm run build`

3. `node build\app.js`

4. Acesso em https://localhost:3000
