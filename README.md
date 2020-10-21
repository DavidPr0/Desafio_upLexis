
Desafio para empresa UpLexis

## Sobre

- Utilizando REGEX para capturar informações do site (https://www.questmultimarcas.com.br/estoque), de acordo com o texto digitado.

## Requisitos
- PHP 7.2+
- Laravel 8+
- MSYQL 5.7+
- Composer

## Orientações
- 1)  Utilize "composer install" para que seja instalado todas as dependências do Projeto.

- 2) Para fazer as configurações você precisa fazendo uma cópia do .env-exemple renomea-lo para
    .env caso não seja gerado automaticamente, trocar as informações dos seguintes trecho de código para acessar a base de dados.

    ```bash
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=
    DB_USERNAME=
    DB_PASSWORD=
    ```
    
- 3) Após instalar as dependências utilize "npm install" para que seja instalado todas as dependências do Webpack. Em seguida utilize "npm run dev" para executar o Webpack.
- 4) Para concluir, execute o camando "php artisan migrate --seed" no terminal para que todas as tabelas sejam criadas e populadas.

## :handshake:
