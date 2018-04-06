Laravel installation
********************
First of all, install Laravel. You can install it globally using Composer:
# composer global require "laravel/installer"
And then use laravel new command for creating a fresh laravel installation in specific directory.
# laravel new todo

Database preparation
********************
Create database todo, that we will use in this project. If you use mysql from terminal:
# mysql -uhomestead -p
# create database todo;
Now go to the ".env" file and set database parameters

Homestead preparation
*********************
Make changes to laravel homestead/Homestead.yaml file to add new project folder to share folder


Package.json
************
# npm install
It’ great, that we have axios out of the box. But we also need to get bulma:
# npm install bulma -S


