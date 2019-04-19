# pikachu
Playground to make CDAP plugins

## How to install
* Install `docker`
* Install `docker-compose`

## How to test CDAP server
* `docker-compose up`
* Go to `localhost:11011` on browser

## How to test java dev environment
* `git clone https://github.com/data-integrations/example-transform`
* `docker-compose run --service-ports shell`
* `mvn clean package`
