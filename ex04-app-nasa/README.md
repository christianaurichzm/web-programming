# app-nasa

Aplicação do tipo SPA (Single Page Application) que utiliza a bilioteca React e o framework CSS Bulma para o desenvolvimento do lado cliente, e o agregador webpack para gerar o arquivo JavaScript que é executado pelo browser.


Ela também acessa e consume dados de um webservice da Nasa.

## Instruções

No diretório servidor editar o arquivo .env atribuindo uma chave a NASA_API_KEY, que é obtida no endereço https://api.nasa.gov/index.html#apply-for-an-api-key 

Isso permitirá que sua aplicação acesse o webservice da Nasa.

1. `npm install`

2. `npm run build`

3. `node build\app.js`

4. Acesso em https://localhost:3000

