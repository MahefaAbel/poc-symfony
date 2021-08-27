# poc-symfony
Symfony Project for POC-ing different things

## Memo Urls
- GET http://sf.poc:81/register/
- POST http://sf.poc:81/api/login_check

## Memo CMD
- composer require friendsofsymfony/user-bundle
- composer require "lexik/jwt-authentication-bundle"
- php bin/console fos:user:create
    - a:1:{i:0;s:10:"ROLE_ADMIN";}
- php bin/console doctrine:schema:update --dump-sql
- php bin/console lexik:jwt:generate-keypair