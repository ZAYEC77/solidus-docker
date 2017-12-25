# solidus-docker
Docker stuff for solidus project

## Setup
```
docker-compose build
docker-compose run app bundle install
docker-compose run app bundle exec rails db:migrate
```

## Run
```
docker-compose up #or docker-compose start
open http://localhost:3000
```
