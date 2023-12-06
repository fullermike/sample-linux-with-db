# sample-linux-with-db

- A simple linux box with postgres database bundled in a docker image where containers share a network.

## First Time
- > docker-compose up

## Stopping instances

- > docker-compose stop

#### Stop services from the terminal where compose start or compose up was performed
- > CTRL + C

## Resume instances (without rebuilding)

#### to start all images
- > docker-compose start

#### to start specific images
- > docker-compose start postgres-db