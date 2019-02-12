# fosuserandeasybundle
Proyecto prueba de symfony con bundles  FOSUSER y EasyAdmin
con symfony 2.4.*, estrucutra de symfony 4.

1). composer create-project symfony/website-skeleton pruebas_1/  "3.4.*"
2). configuración de host 
3). configuración de estrucutra 
4). Instalción de fosuser: composer require friendsofsymfony/user-bundle
5). configuración del bundle, migracion de la entitad user a la DB:  php bin/console doctrine:migrations:diff
6). migracion a la BD : php bin/console doctrine:migrations:migrate
7). posibles rutas: http://localhost/fosuserandeasybundle/public/index.php/register
