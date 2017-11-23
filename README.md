# Laravel

-- Laravel Framework

-- Installation

Steps::
sudo apt-get install php

php -v

//install the Mbstring PHP Extension.
sudo apt-get install php7.0-mbstring

//The XML PHP Extension.
sudo apt-get install php-xml

//And the ZIP PHP Extension.
sudo apt-get install php7.0-zip

//Install Curl
sudo apt-get install curl

The Laravel uses the composer to manage your dependencies, so the next step is install Composer.

curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer

composer global require "laravel/installer"

echo 'export PATH="$HOME/.composer/vendor/bin:$PATH"' >> ~/.bashrc

source ~/.bashrc


//Restart Terminal

//create new project blog

laravel new blog


//Run the Laravel server. Enjoy!

php artisan serve


//Ref: https://medium.com/@rgdev/how-to-install-laravel-5-4-on-ubuntu-16-04-from-scratch-quickly-29375e18e7ca




