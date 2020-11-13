# Insta MVP

Demo: <https://insta-mvp-web.herokuapp.com/>

## Local deploy

```sh
docker-compose build
docker-compose run web npm i
docker-compose run api rails db:reset
docker-compose up
```

**http://localhost:3000/api/v1** - Api service

**http://localhost:3001** - Web service
