# GoEat

Para utilizar este projeto é necessário:
1. instalar o composer e instalar a pasta vendor e para isso é necessário usar o seguinte comando no terminal
   
        composer require nesbot/carbon

2. note que foi criado um ficheiro composer.json, apague o conteudo e adicione

        {
            "require": {
                "nesbot/carbon": "^2.67",
                "phpmailer/phpmailer": "^6.8"
            },
        
            "autoload":{
                "classmap": ["src"]
            }
        }
   
3. criar um ficheiro .config na pasta src
   
       HOSTNAME=localhost
       USERNAME=root //ou outro nome que tenha na base de dados
       PASSWORD= //sua password da base de dados
       DBNAME=GoEat
       DBPORT=3306

4.
