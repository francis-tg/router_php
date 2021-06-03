# router_php

# SIMPLE PHP ROUTER

## Auteur : Francis ALAPHIA

## Email : francisalaphia5@gmail.com

#  Comment ça marche?: 

````php

require __DIR__.'../../vendor/autoload.php';

use App\Handler\Blog;
use App\Router;


$router = new Router();

$router->get('/', function ())
{
    require 'view/home.php';
}



````
