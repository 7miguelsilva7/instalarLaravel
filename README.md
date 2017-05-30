# instalarLaravel

## PHP & Composer

    * Habilitar o php do Xampp globalmente

    sudo ln -s /opt/lampp/bin/php /usr/local/bin/php

    * Instalar Curl 
    
    sudo apt-get install curl

    * Instalar composer 
    
    sudo curl -sS https://getcomposer.org/installer | php
    
    * Habilitar composer globalmente

    sudo mv composer.phar /usr/local/bin/composer

Agora:: poderá usar "composer" Globalmente!

## Instalar Laravel

* composer global require "laravel/installer"
* nano .bashrc
* export PATH="$PATH:$HOME/.config/composer/vendor/bin"
* source ~/.bashrc
* export PATH="$PATH:$HOME/.config/composer/vendor/bin"
* laravel new NomeProjeto
