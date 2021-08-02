
#1
Install composer: https://getcomposer.org/doc/00-intro.md

#2
clone projeto github: git clone https://github.com/Welington6991/handyhostel.git

#3
Alterar dados para acessar o banco MySql no .env na raiz do projeto para conectar em seu banco MySql:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=8889
DB_DATABASE=handyhostel
DB_USERNAME=root
DB_PASSWORD=root

#4
Pegue o arquivo handyhostel.sql na raiz do projeto e importe no seu banco MySql.
#4.1
Você também tem a opção de rodar o camando: php artisan migrate que o mesmo irá criar as tables em seu banco, o banco será o que você colocou no .env

#5
No terminal de comando acesse a pasta do projeto e rode o comando: composer install

#6
Para rodar o projeto execute: php artisan serve, por padrão o host do site é: localhost:8000