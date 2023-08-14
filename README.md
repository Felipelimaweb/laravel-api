# Laravel Api

Para rodar essa aplicação é necessário ter instalado Apache, Mysql, PHP e Composer

# Instalação
1. Clone o repositorio
```
https://github.com/Felipelimaweb/laravel-api
```

2. Instale os pacotes com o composer
```
cd laravel-api
$ composer install
```

3. Creie e configure o arquivo .env
```
Copie o arquivo .env.example e renomeie para .env
$ php artisan key:generate
Coloque as credenciais do banco de dados no .env
```

4. Rode as migrations
```
$ php artisan migrate
```