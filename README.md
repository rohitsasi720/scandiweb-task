## Scandiweb Junior Developer Test

CRUD e-commerce website

## Project Info

A web-app (accessible by an URL) containing two pages for:

* Product list page.
* Adding a product page.
URL : https://rohitscandiweb.000webhostapp.com/ 

## Setup

# Build using docker compose : 
* Make sure you have docker desktop and docker compose already installed.
 If you dont have docker compose installed follow this documentation : https://docs.docker.com/compose/install/ 
* Run the command 
```bash
docker-compose up -d
``` 
* Open ``localhost:8000`` to access the website and ``localhost:8001`` to access phpmyadmin panel


# Building on local machine :
* Open terminal 
* Run ``cd /xampp/htdocs/folder-name``
* Git clone
* Download and install composer from https://getcomposer.org/
* Check config.php and make the required changes mentioned there
* Start Apache and MYSQL on Xampp
* Open the folder and run composer update in the terminal
* Run ``cd /xampp/htdocs/folder-name/public``
* Run PHP development server ``php -S localhost:8080``

