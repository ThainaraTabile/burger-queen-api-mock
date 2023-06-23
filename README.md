# Burger Queen API Mock

Utilizando as bibliotecas [json-server](https://github.com/typicode/json-server) 
e [json-server-auth](https://github.com/jeremyben/json-server-auth) 
foi criado um mock para a 
[Burger Queen API](https://app.swaggerhub.com/apis/ssinuco/BurgerQueenAPI/2.0.0)

## Execução

1. Clone o repositório
2. Instale as dependências
    ```bash
    npm install
    ```
3. Execute o Mock
    ```bash
    npm start
    ```
4. Agora você pode acessar os endpoints da API descritos na 
[documentación](https://app.swaggerhub.com/apis/ssinuco/BurgerQueenAPI/2.0.0) 
usando como URL base [http://localhost:8080/](http://localhost:8080/).

  Conforme indicado na documentação, os endpoints são protegidos por token de autenticação.

## Informação

O mock _out-of-the-box_ fornece informações sobre usuários:
<br><br>
Administrador adm@bs.com
<br><br>
Cozinheiro: cozinha@bs.com
<br><br>
Atendente: atendimento@bs.com
A senha para ambos usuários é _1234567_

Também são fornecidas informações sobre produtos e pedidos.
