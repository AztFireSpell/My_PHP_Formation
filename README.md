# My_PHP_Formation orientado a objetos proyecto

Ejecutamos composer, para agregar phpunit para pruebas

composer require --dev phpunit/phpunit

En composer.json agregamos:

    "name": "aztfirespell/post",
    "description": "proyecto orientado a objetos",
    "autoload": {
        "psr-4": {
            "App\\": "src/" 
        }
    },

    y ejecutamos composer dump
