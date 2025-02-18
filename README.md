# INSTALLATIONS REQUIRED IN NEW HARDWARE
https://www.youtube.com/watch?v=kPGcIyxYfBE

## git

## ssh key
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account


## xampp


## xdebug


## vscode


## composer
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


## php unit


## laravel
To Install Globally, run from Terminal :

composer global require laravel/installer

Run to create each project (in Terminal from the folder where the project is going to be stored) :

laravel new project_name


## mongodb
https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/

First, open an account in the website of Mongo Atlas

Install MongoDB Community Edition, use link above.


To start Mongo DB as a macOS service (version in Mac MINI) :

brew services start mongodb-community@8.0

To stop a mongod running as a macOS service (version in Mac Mini) :

brew services stop mongodb-community@8.0


To start Mongo DB as a macOS service (version in iMac) :

brew services start mongodb-community@7.0

To stop a mongod running as a macOS service (version in iMac) :

brew services stop mongodb-community@7.0


THIS IS THE RIGHT ONE I GOT IN TERMINAL AFTER INSTALLATION : To start mongodb/brew/mongodb-community and restart at login :

brew services start mongodb/brew/mongodb-community

Install Mongo DB Compass GUI (Graphic User Interface)

brew install mongodb-compass

Install Mongo DB Extension in VS Code


## git kraken
