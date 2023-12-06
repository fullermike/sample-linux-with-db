# sample-linux-with-db

- A simple linux box with postgres database bundled in a docker image where containers share a network.

## First Time
- > docker-compose up

## Stopping or Starting instances

- > docker-compose stop
- > docker-compose start

#### Stop services from the terminal where compose start or compose up was performed
- > CTRL + C

## Resume instances (without rebuilding)

#### Start all images
- > docker-compose start

#### Start specific images
- > docker-compose start postgres