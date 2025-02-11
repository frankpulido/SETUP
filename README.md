# INSTALLATIONS REQUIRED IN NEW HARDWARE
https://www.youtube.com/watch?v=kPGcIyxYfBE

### git

### ssh key
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

### xampp

### xdebug

### vscode


### composer
https://www.youtube.com/watch?v=89x8EMhtyuA

To Install Globally, run from Terminal :

php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"

php composer-setup.php

php -r "unlink('composer-setup.php');"

After running the previous 3 commands, check using :

php composer.phar --version

Last, to make it accesible anywhere :

sudo mkdir -p /usr/local/bin/

sudo mv composer.phar /usr/local/bin/composer

composer -v


### php unit

### laravel
To Install Globally, run from Terminal :
composer global require laravel/installer
Run to create each project (in Terminal from the folder where the project is going to be stored) :
laravel new <project name>

### git kraken
